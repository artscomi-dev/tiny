


# @artscomi/tiny

![npm (scoped)](https://img.shields.io/npm/v/@artscomi/tiny)
[![install size](https://packagephobia.com/badge?p=@artscomi/tiny@2.0.0)](https://packagephobia.com/result?p=@artscomi/tiny@2.0.0)


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
