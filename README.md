# boilerplate-es6

> boilerplate-es6 is a template for your es6 based projects using

## Install

```sh
## Clone the repo
$ git clone git@github.com:stefanwalther/boilerplate-es6.git

## Install all dependencies
$ npm install
```

## Basic concept

* JavaScript ES6
* ES6 Transpiler
  - [babel](https://babeljs.io/)
* Build system
  - [gulp](http://gulpjs.com/)
* Test framework
  - [mocha](https://mochajs.org/)
  - [istanbul](https://istanbul.js.org/) & [nyc](https://github.com/istanbuljs/nyc)

* Code style
  - [idiomatic](https://github.com/rwaldron/idiomatic.js/)
  - [eslint](http://eslint.org/) (using JS code style idiomatic)

* Documentation
  - [verb](https://github.com/verbose/verb)

## Script Tasks

### build

> Build the code from `./src`, store in `./dist`

```sh
$ npm run build
```

### Test

```sh
## Unit tests
$ npm run test:unit

## E2E tests
$ npm run test:e2e

## All tests
$ npm run test
```

### Test coverage

```sh
$ npm run coverage
```

### Linting

```sh
## Lint `./src`
$ npm run lint

## Lint './test`
$ npm run lint:test
```

### Documentation

```sh
## Globally install verb and verb-cli
$ npm install verb verb-cli -g

## Generated documentation using verb
$ npm run docs
```

## Tool configuration - Webstorm

## Author

**Stefan Walther**

+ [github/stefanwalther](https://github.com/stefanwalther)
* [twitter/waltherstefan](http://twitter.com/waltherstefan)

## License

MIT

***

_This file was generated by [verb-cli](https://github.com/assemble/verb-cli) on March 23, 2017._
