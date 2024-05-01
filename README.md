# @f1stnpm3/laborum-blanditiis-id <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Get the byte length of an ArrayBuffer, even in engines without a `.byteLength` method.

## Example

```js
const assert = require('assert');
const byteLength = require('@f1stnpm3/laborum-blanditiis-id');

assert.equal(byteLength([]), NaN, 'an array is not an ArrayBuffer, yields NaN');

assert.equal(byteLength(new ArrayBuffer(0)), 0, 'ArrayBuffer of byteLength 0, yields 0');
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@f1stnpm3/laborum-blanditiis-id
[npm-version-svg]: https://versionbadg.es/inspect-js/@f1stnpm3/laborum-blanditiis-id.svg
[deps-svg]: https://david-dm.org/inspect-js/@f1stnpm3/laborum-blanditiis-id.svg
[deps-url]: https://david-dm.org/inspect-js/@f1stnpm3/laborum-blanditiis-id
[dev-deps-svg]: https://david-dm.org/inspect-js/@f1stnpm3/laborum-blanditiis-id/dev-status.svg
[dev-deps-url]: https://david-dm.org/inspect-js/@f1stnpm3/laborum-blanditiis-id#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@f1stnpm3/laborum-blanditiis-id.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@f1stnpm3/laborum-blanditiis-id.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@f1stnpm3/laborum-blanditiis-id.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@f1stnpm3/laborum-blanditiis-id
[codecov-image]: https://codecov.io/gh/inspect-js/@f1stnpm3/laborum-blanditiis-id/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@f1stnpm3/laborum-blanditiis-id/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@f1stnpm3/laborum-blanditiis-id
[actions-url]: https://github.com/f1stnpm3/laborum-blanditiis-id/actions
