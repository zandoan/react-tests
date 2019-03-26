# Testing React Applications Examples

This repo showcases how to test various parts of a common React/Redux app using Mocha, `expect` and `enzyme`.

## Setup

1. `git clone git@github.com:zandoan/react-tests`

2. `cd react-testing`

3. `npm install`

## Structure

```rb

examples/
├── add       # Simple example of a unit test
├── NavBar    # Redux actions and reducer tests

```

## Trying the tests

There's a bunch of commands to run different test "classes". The main command is

### Run all tests

Run the entire test suite.

```
$ npm run test
```

### Other commands

- `$ npm run test:function`: Run the pure function tests

- `$ npm run test:actions`: Run the action tests

- `$ npm run test:reducer`: Run the reducer tests

- `$ npm run test:redux`: Run both reducer and action tests

- `$ npm run test:component`: Run the component tests

- `$ npm run test:react`: Run all the redux tests and the component tests
