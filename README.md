# eslint-config-monaverse[![](https://badge.fury.io/js/eslint-config-monaverse.svg)](https://npmjs.org/package/eslint-config-monaverse)

> My personal ESLint configurations [`eslint`](https://eslint.org) configurations

## Requirements

- `eslint >7.X.X`

## Basic Usage

**Install**

```bash
$ npm install -D eslint-config-monaverse
```

**Create `.eslintrc.js`**

```javascript
// .eslintrc.js

module.exports = {
  extends: ["monaverse/<extension name>"],
};
```

## Available Extensions

- `es6`
- `typescript`
- `react` (for ES6)
- `react-with-typescript`
- `react-native` (for ES6)
- `react-native-with-typescript`
- `vue` (for ES6)
- `vue-with-typescript`

## Examples

```javascript
// .eslintrc.js

module.exports = {
  extends: ["monaverse/typescript"],
};
```

```javascript
// .eslintrc.js

module.exports = {
  extends: ["monaverse/react-with-typescript"],
};
```
