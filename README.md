[![GitHub license](https://img.shields.io/github/license/sompura/first)](https://github.com/sompura/first)

Removes all spaces from a string.

## Install

```
$ npm install @sompura/first
```

## Usage

```js
const tiny = require("@sompura/first");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: First wants a string!
//    at first (<anonymous>:2:41)
//    at <anonymous>:1:1
```
