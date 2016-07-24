[![Build Status](https://travis-ci.org/kaelzhang/babel-npm.svg?branch=master)](https://travis-ci.org/kaelzhang/babel-npm)
<!-- optional appveyor tst
[![Windows Build Status](https://ci.appveyor.com/api/projects/status/github/kaelzhang/babel-npm?branch=master&svg=true)](https://ci.appveyor.com/project/kaelzhang/babel-npm)
-->
<!-- optional npm version
[![NPM version](https://badge.fury.io/js/babel-npm.svg)](http://badge.fury.io/js/babel-npm)
-->
<!-- optional npm downloads
[![npm module downloads per month](http://img.shields.io/npm/dm/babel-npm.svg)](https://www.npmjs.org/package/babel-npm)
-->
<!-- optional dependency status
[![Dependency Status](https://david-dm.org/kaelzhang/babel-npm.svg)](https://david-dm.org/kaelzhang/babel-npm)
-->

# babel-npm

An babeled npm to install and transform dependencies for old node.

**NOT DONE YET, CONTRIBUTION WANTED**

## Install

```sh
$ npm i -g babel-npm
```

## Usage

Write package `foo` in es6, es7 with package field `engines.node` >= 6.0.0.

If we install `foo` with node 4

```sh
babel-npm install foo --save
```

It works!

## License

MIT
