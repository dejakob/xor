# XOR

[![Build Status](https://travis-ci.org/dejakob/xor.svg?branch=master)](https://travis-ci.org/dejakob/xor)
[![NPM](https://img.shields.io/npm/v/xor/latest.svg?label=npm)](https://npmjs.com/package/xor)

Logical xor operator for JS

## Boolean table

| Condition | Condition | Output |
|-----------|–----------|--------|
| false     | false     | false  |
| false     | true      | true   |
| true      | false     | true   |
| true      | true      | false  |

## Usage

```js
const xor = require('@dejakob/xor');

xor(true, false) // will return true
```