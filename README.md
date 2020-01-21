# node-ts-jest

A blank slate Node.js project using Typescript with ESLint + Prettier, and using Jest for unit testing.
Includes Express.

## npm scripts

`npm start` will run the server and use nodemon to watch .ts files for changes and trigger a rebuild.
`npm test` runs jest on all files in the /tests/ dir.
`npm compile` is only really used for the `start` task, in order to drigger a rebuild and re-run.
