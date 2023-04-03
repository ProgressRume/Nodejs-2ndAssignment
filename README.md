# Nodejs-2ndAssignment
### Assignment Solution
#### 1. What is Event loop?

Event loop in node js is an array of callbacks used to process asynchronous tasks. Event loop allows for asynchronous tasks to be performed.

 #### 2. Explain the 6 phases of the event loop

- Timers: This is the stage where functions that perform callbacks after a given amount of time are processed.

- Pending and idle: This is the stage where external files are read   

- Prepare: This is the phase where the system gathers information, and prepares what needs to be executed during the next phase of the Event Loop.

- Polling: In this phase, input/output callbacks are processed such as readfile, writefile etc.

- Check: This is the phase where setImmediate timers as part of the input/output are executed

-Close: This is the last phase where if there are no timers or input/output left, the event loop closes and the timer ends.

#### 3. List some best practices in server-side code development
- Keep Code Small
When writing codes, it is better to keep the applications scalable and services should be kept separate.  This can be achieved by modularisation.

- Use formatters such as Prettier for syntactical consistency.

- Focus on code quality
Each code should be written in a way that another person can easily understand and work with it.

- Use of TypeScript and Unit Testing to create consistency and reduce
developer errors when writing code.

- Follow a JavaScript linting tool such as ESLint. 

#### 4. What is NPM5: How do you initialize a package in npm

NPM meaning Node Package Manager is a tool used for managing project dependencies via a command line and a website that hosts over 1 million packages. NPM can be used to create an application, track an application, track node dependencies, install third party packages etc

To initialise, type npm init

#### 5. How do you run a script in the package.json ?
npm run "NAME-OF-YOUR-SCRIPT" command
