# remark-mathjax

[![standard-readme compliant][standard-readme-badge]][standard-readme]
[![LICENSE][license-badge]][license]
[![NPM][npm-badge]][npm]
[![CircleCI][circleci-badge]][circleci]

[npm]: https://www.npmjs.com/package/@paperist/remark-mathjax
[license]: https://3846masa.mit-license.org
[circleci]: https://circleci.com/gh/Paperist/remark-mathjax
[standard-readme]: https://github.com/RichardLitt/standard-readme

[npm-badge]: https://img.shields.io/npm/v/@paperist/remark-mathjax.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAACAAAAAgBAMAAACBVGfHAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAAbUExURcwAAOeIiP////G7u/ri4tIZGdpFReJsbPC3t075sZwAAAAvSURBVCjPY2CgDWAThIMEsACjEhwIUCZg0dGCIqASwMAxMgXAgSzOwMAOC2TqAwBvzR4JxLaP0gAAAABJRU5ErkJggg==
[license-badge]: https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQBAMAAADt3eJSAAAAIGNIUk0AAHomAACAhAAA%2BgAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAAVUExURSBTICJcIiNgIiZoJTuhNyt3Kf///%2BCqxSgAAAAGdFJOUwpclbn%2B4Fj6/H8AAAABYktHRAZhZrh9AAAACXBIWXMAAA3XAAAN1wFCKJt4AAAAB3RJTUUH4AkEEjEV7MDQQwAAAGBJREFUCNc1TUEKgDAMi07vE/Q%2BRD8g%2B4BbvAvi/79iMjDQJm1CC6BbDzRsZI3incIpYeYFhCaYnLiyPYnYkwWZFWoFHrSuttCmmbwXh0eJQYVON4JthZTxCzzAmyb8%2BAAKXBRyN6RyZQAAAABJRU5ErkJggg==
[circleci-badge]: https://img.shields.io/circleci/project/Paperist/remark-mathjax/master.svg?style=flat-square&logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQEAYAAABPYyMiAAAAIGNIUk0AAHomAACAhAAA%2BgAAAIDoAAB1MAAA6mAAADqYAAAXcJy6UTwAAAAGYktHRP///////wlY99wAAAAHdElNRQfgCQQSJS8EYt6kAAAAiklEQVRIx2M41nqs9Xi9WDQh%2BjQQnDnz%2BS5x9KS9xJrLgN/CSXtJs5h0BzHQ1mLCDmEgL4jJpyl0AOG4JTYE4Q6gdqIi1UMM2F1OrE9xBy2xDmGgrs8wHU5nB2CGBNEOQPcBoaigThQA08AgS4QDkA3pXRChe4SBskqHiiUhreoEsmtDyhxEfKIFAG4yoGuqR9fTAAAAAElFTkSuQmCC
[standard-readme-badge]: https://img.shields.io/badge/standard--readme-OK-green.svg?style=flat-square

> wooorm/remark plugin for mathjax

## Table of Contents

- [Install](#install)
- [Usage](#usage)
- [Contribute](#contribute)
- [License](#license)

## Install

```
npm i remark @paperist/remark-mathjax
```

## Usage

```js
const remark = require('remark');
const mathjax = require('remark-mathjax');

const ast = remark().use(mathjax).parse(markdown);
console.dir(ast, { depth: null });
```

## Contribute

PRs accepted.

## License

MIT © 3846masa
