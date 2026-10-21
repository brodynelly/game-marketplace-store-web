# GameStore

A web development course project from the University of Missouri. The repository contains an Angular frontend and a Node/Express backend; this is a coursework project, not a verified production store.

## Requirements

- Node.js and npm
- The database/configuration required by the backend, as defined in the source

## Install and run

The package manifest provides an install script that uses npm's legacy peer dependency resolution:

~~~sh
npm run install-deps
npm run start
~~~

The combined start script launches the Angular frontend and Node backend. To start either side separately, use the start:frontend or start:backend script.

## Available checks

- The build script builds the Angular frontend.

There is no test script or automated test suite configured in the package manifest, so this repository does not claim test coverage.

## Project structure

- **src/** — Angular frontend
- **backend/** — Express application and database connection
- **server.js** — HTTP server entry point

Generated npm cache data and operating-system metadata are excluded from the repository; keep dependency manifests and lockfiles under version control.