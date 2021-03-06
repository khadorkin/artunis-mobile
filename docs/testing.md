# Testing

## Unit tests
`yarn test` runs the unit test suite.

Our tests are written using [Jest](https://facebook.github.io/jest/).

To write a test, place a Javascript file with the `-test.js` suffix in the
`__tests__` directory inside of any subfolder of `/src`. The test will be
automatically picked up by the test runner.


## Linting
`yarn run test:lint` checks the codebase against our linting rules. We're using
the AirBnB [ES6](https://github.com/airbnb/javascript) and
[React](https://github.com/airbnb/javascript/tree/master/react) style guides.

## Type checking with Flow
Use [Flow](https://flowtype.org/) and [flow-typed](https://github.com/flowtype/flow-typed) to find and prevent type related issues.
