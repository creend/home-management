# Home Management Application
## Overview

The Home Management Application is a versatile tool designed to help users organize and manage various aspects of their home environment. This includes task scheduling, maintenance tracking, budget management, and more. Developed using modern web technologies, it offers a user-friendly interface and robust functionality to streamline household management tasks.

## Installation

Before running the application, ensure that Node.js and npm (Node Package Manager) are installed on your system. Clone the repository and navigate to the application directory. Run the following command to install dependencies:

```bash
npm install
```

## NPM Scripts

The `package.json` includes several scripts that facilitate common tasks:

```bash
npm run prepare # Sets up git hooks using Husky.
npm run start # Starts the development server.
npm run build # Creates a production build of the application.
npm run test # Runs tests across all projects in parallel.
npm run lint:check # Checks for linting errors across all projects.
npm run lint:fix # Automatically fixes linting issues across all projects.
npm run format:fix # Formats the codebase using Prettier configuration.
npm run format:check # Checks the code format against the Prettier configuration.
npm run circular-deps:check # Identifies circular dependencies in TypeScript files.
npm run code:check # Comprehensive check for code format and linting errors.
npm run code:fix # Comprehensive command to fix both format and linting issues.
```