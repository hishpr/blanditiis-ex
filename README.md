# @hishpr/blanditiis-ex <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

A simple list of possible Typed Array names.

## Example

```js
const assert = require('assert');

const names = require('@hishpr/blanditiis-ex');

assert(Array.isArray(names));
assert(names.every(name => (
    typeof name === 'string'
    && typeof globalThis[name] === 'function'
    && globalThis[name].name === name
)));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

## Security

Please email [@ljharb](https://github.com/ljharb) or see https://tidelift.com/security if you have a potential security vulnerability to report.

[package-url]: https://npmjs.org/package/@hishpr/blanditiis-ex
[npm-version-svg]: https://versionbadg.es/ljharb/@hishpr/blanditiis-ex.svg
[deps-svg]: https://david-dm.org/ljharb/@hishpr/blanditiis-ex.svg
[deps-url]: https://david-dm.org/ljharb/@hishpr/blanditiis-ex
[dev-deps-svg]: https://david-dm.org/ljharb/@hishpr/blanditiis-ex/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@hishpr/blanditiis-ex#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@hishpr/blanditiis-ex.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@hishpr/blanditiis-ex.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@hishpr/blanditiis-ex.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@hishpr/blanditiis-ex
[codecov-image]: https://codecov.io/gh/ljharb/@hishpr/blanditiis-ex/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@hishpr/blanditiis-ex/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@hishpr/blanditiis-ex
[actions-url]: https://github.com/hishpr/blanditiis-ex/actions
