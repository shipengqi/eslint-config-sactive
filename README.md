# eslint-config-sactive

SActive's ESLint config, based on Standard.

[![Build status][travis-image]][travis-url]
[![NPM version][npm-image]][npm-url]
[![NPM Download][npm-download]][npm-url]
[![License][license-image]][license-url]


[![NPM](https://nodei.co/npm/eslint-config-sactive.png?downloads=true)](https://nodei.co/npm/eslint-config-sactive/)

## Usage

```bash
npm install --save-dev \
eslint \
eslint-config-sactive \
eslint-config-standard \
eslint-plugin-standard \
eslint-plugin-promise \
slint-plugin-import \
eslint-plugin-node

#or
yarn add eslint \
eslint-config-sactive \
eslint-config-standard \
eslint-plugin-standard \
eslint-plugin-promise \
eslint-plugin-import \
eslint-plugin-node --dev
```

Add this to your `.eslintrc` file:
```javascript
{
  "extends": "sactive"
}
```

[npm-image]: https://img.shields.io/npm/v/eslint-config-sactive.svg
[npm-url]: https://www.npmjs.com/package/eslint-config-sactive
[travis-image]: https://travis-ci.org/shipengqi/eslint-config-sactive.svg?branch=master
[travis-url]: https://www.travis-ci.org/shipengqi/eslint-config-sactive
[npm-download]: https://img.shields.io/npm/dw/eslint-config-sactive.svg
[license-image]: http://img.shields.io/npm/l/eslint-config-sactive.svg
[license-url]: ./LICENSE