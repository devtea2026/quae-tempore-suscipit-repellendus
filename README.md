# @devtea2026/quae-tempore-suscipit-repellendus <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Determine whether the environment has the so-called "override mistake" - [[Set]]ing a property whose ancestor is nonwritable throws.

## Example

```js
var hasOverrideMistake = require('@devtea2026/quae-tempore-suscipit-repellendus');
var assert = require('assert');

assert.equal(typeof hasOverrideMistake(), 'boolean', 'returns true or false');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@devtea2026/quae-tempore-suscipit-repellendus
[npm-version-svg]: https://versionbadg.es/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus.svg
[deps-svg]: https://david-dm.org/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus.svg
[deps-url]: https://david-dm.org/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus
[dev-deps-svg]: https://david-dm.org/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@devtea2026/quae-tempore-suscipit-repellendus.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@devtea2026/quae-tempore-suscipit-repellendus.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@devtea2026/quae-tempore-suscipit-repellendus.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@devtea2026/quae-tempore-suscipit-repellendus
[codecov-image]: https://codecov.io/gh/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@devtea2026/quae-tempore-suscipit-repellendus
[actions-url]: https://github.com/devtea2026/quae-tempore-suscipit-repellendus/actions
