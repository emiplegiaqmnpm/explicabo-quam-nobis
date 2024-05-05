# @emiplegiaqmnpm/explicabo-quam-nobis <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @emiplegiaqmnpm/explicabo-quam-nobis
```

## Usage/Examples

```js
var regexTester = require('@emiplegiaqmnpm/explicabo-quam-nobis');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@emiplegiaqmnpm/explicabo-quam-nobis
[npm-version-svg]: https://versionbadg.es/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis.svg
[deps-svg]: https://david-dm.org/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis.svg
[deps-url]: https://david-dm.org/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis
[dev-deps-svg]: https://david-dm.org/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@emiplegiaqmnpm/explicabo-quam-nobis.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@emiplegiaqmnpm/explicabo-quam-nobis.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@emiplegiaqmnpm/explicabo-quam-nobis.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@emiplegiaqmnpm/explicabo-quam-nobis
[codecov-image]: https://codecov.io/gh/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@emiplegiaqmnpm/explicabo-quam-nobis
[actions-url]: https://github.com/emiplegiaqmnpm/explicabo-quam-nobis/actions
