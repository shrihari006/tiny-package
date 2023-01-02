# @shrihari006/tiny-package

[![npm (scoped)](https://img.shields.io/npm/v/@shriharim006/tiny-package)](https://www.npmjs.com/package/@shriharim006/tiny-package)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/tiny-package)](https://www.npmjs.com/package/@shriharim006/tiny-package)

Removes all spaces from a string.

## Install

```
$ npm i @shriharim006/tiny-package
```

## Usage

```js
const tiny = require("@shrihari006/tiny-package");
tiny("So much space!");
//=> "Somuchspace!"
tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
