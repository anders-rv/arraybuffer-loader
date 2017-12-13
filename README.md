ArrayBuffer loader for webpack
------------------------------

[![npm](https://img.shields.io/npm/v/arraybuffer-loader.svg?maxAge=2592000&style=flat-square)](https://www.npmjs.org/package/arraybuffer-loader)
[![Travis](https://img.shields.io/travis/pine/arraybuffer-loader/master.svg?maxAge=2592000&style=flat-square)](https://travis-ci.org/pine/arraybuffer-loader)
[![Build Status](https://img.shields.io/appveyor/ci/pine/arraybuffer-loader/master.svg?style=flat-square&maxAge=2592000)](https://ci.appveyor.com/project/pine/arraybuffer-loader/branch/master)
[![Dependency Status](https://img.shields.io/david/pine/arraybuffer-loader.svg?maxAge=2592000&style=flat-square)](https://david-dm.org/pine/arraybuffer-loader)
[![devDependency Status](https://img.shields.io/david/dev/pine/arraybuffer-loader.svg?maxAge=2592000&style=flat-square)](https://david-dm.org/pine/arraybuffer-loader?type=dev)


## Getting Started

```
$ npm install arraybuffer-loader --save-dev
```

## Usage

See offical document [Loaders](https://webpack.js.org/concepts/loaders/).

```js
var buffer = require('arraybuffer!./data.dat')
var array  = new Uint8Array(buffer)

// Enjoy!!
```

## License
MIT &copy; Pine Mizune
