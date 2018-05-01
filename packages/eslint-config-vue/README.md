# @zonedigital/eslint-config-vue

[![npm][npm-image]][npm-url] [![downloads][downloads-image]][npm-url]

[npm-image]: https://img.shields.io/npm/v/@zonedigital/eslint-config-vue.svg?style=flat-square
[npm-url]: https://npmjs.org/package/@zonedigital/eslint-config-vue
[downloads-image]: https://img.shields.io/npm/dm/@zonedigital/eslint-config-vue.svg?style=flat-square

This package provides Zone's JavaScript style guide for Vue as an extensible shared config.

It is part of [Zone Frontend](https://github.com/zone/frontend).

## Requirements

As this package is a config, you'll need to ensure you've installed any peer dependencies.

### Yarn

`yarn add eslint eslint-plugin-import eslint-plugin-vue`

### NPM

`npm i eslint eslint-plugin-import eslint-plugin-vue`

## Installation

### Yarn

`yarn add @zonedigital/eslint-config-vue`

### NPM

`npm i @zonedigital/eslint-config-vue`

## Usage

Add the Zone rules to your eslint config. Be sure to add as the last item.

```javascript
{
  "extends": [..., "@zonedigital/eslint-config-vue"],
  // ... project config here, if any ...
}
```

**Optional but recommended:** Remove duplicated rules from your eslint config.