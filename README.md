woff2 for node.js (via WebAssembly)
===================================

[![CI](https://github.com/fontello/wawoff2/actions/workflows/ci.yml/badge.svg)](https://github.com/fontello/wawoff2/actions/workflows/ci.yml)
[![NPM version](https://img.shields.io/npm/v/wawoff2.svg?style=flat)](https://www.npmjs.org/package/wawoff2)

Google's [woff2](https://github.com/google/woff2) build for `browser`, using WebAssembly. 

Install
-------

```sh
npm install @ffutop/wawoff2
```


Use Example
-----------

```js
import { woff2compress, woff2decompress } from '@ffutop/wawoff2';

// src - Uint8Array
woff2compress(src).then(out => {
  // store result
});
```
