


# @artscomi/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@artscomi/tiny.svg)](https://www.npmjs.com/package/@artscomi/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@artscomi/tiny.svg)](https://www.npmjs.com/package/@artscomi/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @artscomi/tiny
```

## Usage

```js
const tiny = require("@artscomi/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```