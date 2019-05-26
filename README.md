# jrb-npm

[![NPM version](https://img.shields.io/npm/v/jrb-npm.svg)](https://www.npmjs.com/package/jrb-npm)
[![license](https://img.shields.io/npm/l/express.svg)]()

A collection of JavaScript utility functions without any dependencies.

## Installation

```
npm i --save jrb-npm
```

## Usgae

```javaScript
var utils = require('jrb-npm')
utils.string.isString('aaa')//true

// or

var util = require('jrb-npm').string
util.isString('aaa')//true
```

## APi

### string

#### isString(value)

Determine whether value is a string.

### number

#### isNum(value)

Determine whether value is a Number.