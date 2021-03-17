# Getting Started

The purpose of this repository is to demonstrate Protractor's ability to run test suites as phases. The original tests were arbitrarily designated as smoke tests, acceptance tests, or regression tests to allow for file separation and execution by a dedicated task.

Executing npm run will list the new e2e test tasks:

```bash
$ npm run

Lifecycle scripts included in angular.io-example:
  start
    ng serve
  test
    ng test

available via `npm run-script`:
  ng
    ng
  build
    ng build
  lint
    ng lint
  e2e
    ng e2e
  e2e:acceptance
    ng e2e "--suite=acceptance"
  e2e:smoke
    ng e2e "--suite=smoke"
  e2e:regression
    ng e2e "--suite=regression"
```

## Original Code

The original Angular app comes from John Papa's [Tour Of Heroes](https://github.com/johnpapa/angular-tour-of-heroes.git)

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Protractor

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests for acceptance

Run `ng e2e:acceptance` to execute the end-to-end Acceptance tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Running end-to-end tests for regression

Run `ng e2e:regression` to execute the end-to-end Regression tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.


## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.0.

