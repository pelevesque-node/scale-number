[![Build Status](https://travis-ci.org/pelevesque/scale-number.svg?branch=master)](https://travis-ci.org/pelevesque/scale-number)
[![Coverage Status](https://coveralls.io/repos/github/pelevesque/scale-number/badge.svg?branch=master)](https://coveralls.io/github/pelevesque/scale-number?branch=master)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

# scale-number

Scales a number within a range.

## Node Repository

https://www.npmjs.com/package/@pelevesque/scale-number

## Installation

`npm install @pelevesque/scale-number`

## Tests

Command                      | Description
---------------------------- | ------------
`npm test` or `npm run test` | All Tests Below
`npm run cover`              | Standard Style
`npm run standard`           | Coverage
`npm run unit`               | Unit Tests

## Usage

```js
const scaleNumber = require('@pelevesque/scale-number')
```

```js
const num = 10
const oldRangeMin = 0
const oldRangeMax = 100
const newRangeMin = 0
const newRangeMax = 1000
const result = scaleNumber(num, oldRangeMin, oldRangeMax, newRangeMin, newRangeMax)
// result === 100
```
