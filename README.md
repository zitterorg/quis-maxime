# @zitterorg/quis-maxime <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @zitterorg/quis-maxime
```

## Usage/Examples

```js
var regexTester = require('@zitterorg/quis-maxime');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@zitterorg/quis-maxime
[npm-version-svg]: https://versionbadg.es/ljharb/@zitterorg/quis-maxime.svg
[deps-svg]: https://david-dm.org/ljharb/@zitterorg/quis-maxime.svg
[deps-url]: https://david-dm.org/ljharb/@zitterorg/quis-maxime
[dev-deps-svg]: https://david-dm.org/ljharb/@zitterorg/quis-maxime/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@zitterorg/quis-maxime#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@zitterorg/quis-maxime.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@zitterorg/quis-maxime.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@zitterorg/quis-maxime.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@zitterorg/quis-maxime
[codecov-image]: https://codecov.io/gh/ljharb/@zitterorg/quis-maxime/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@zitterorg/quis-maxime/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@zitterorg/quis-maxime
[actions-url]: https://github.com/zitterorg/quis-maxime/actions
