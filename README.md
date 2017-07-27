# get-root-module

> Traverses up the directory tree and returns the first module found

[![Build Status](https://travis-ci.org/lukechilds/get-root-module.svg?branch=master)](https://travis-ci.org/lukechilds/get-root-module)
[![Coverage Status](https://coveralls.io/repos/github/lukechilds/get-root-module/badge.svg?branch=master)](https://coveralls.io/github/lukechilds/get-root-module?branch=master)
[![npm](https://img.shields.io/npm/v/get-root-module.svg)](https://www.npmjs.com/package/get-root-module)

Useful in tests so you don't have to require the package you're testing via relative paths.

Starts directory traversal from `process.cwd()` so this should really only be used in tests or CLI apps.

## Install

```shell
npm install --save get-root-module
```

## License

MIT © Luke Childs
