# testes

Project with study purpose, where I put in pratice good habits in testing methods.

## What is used

- javascript
- jest
- babel

## Usage

In this project each file that contains the implementation of methods, has also a file with the same name but with .spec.js in the end, that contains the test suit. Ex: calculator.js => calculator.espec.js

## Getting Started

Type git clone https://github.com/ydroulis/testes.git to clone the project in your directory

Then run npm install or yarn add to install alll the dependencies

Now, to run all the test:

```bash
npm test
# or
yarn test
```

If you want to run all the tests automatically whenever you save some modification:

```bash
npm test:watch
# or
yarn test:watch
```

To get a report with tests coverage:

```bash
npm test --coverage
# or
yarn test --coverage
```
