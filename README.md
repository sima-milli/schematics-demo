![GitHub package.json version](https://img.shields.io/github/package-json/v/sima-milli/schematics-demo)

# Custom Angular Components Using Schematics

A custom reusable Angular schematics project to generate stepper wizard

## Prerequisites

Node.js 6.9+
Angular CLI (globally installed)
Schematics CLI (globally installed)

**Remember to run an `npm install` the first time you run the project, to ensure the dependencies are installed.

## Generate component

To generate this stepper wizard in your project, install this package and run: 
```bash
ng generate schematics-demo:schematics-demo --name=YOUR-COMPONENT-NAME
```

## Run locally
```bash
npm start
``` 

## Testing

To test locally, install `@angular-devkit/schematics-cli` globally and use the `schematics` command line tool. That tool acts the same as the `generate` command of the Angular CLI, but also has a debug mode.

Check the documentation with
```bash
schematics --help
```

## Unit Testing

`npm run test` will run the unit tests, using Jasmine as a runner and test framework.


 
