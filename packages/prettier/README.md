# Configuration - Prettier

My personal configuration for [Prettier](https://prettier.io/)

## Usage

Install via NPM:

```
npm i @crgeary/configuration-prettier --save-dev
```

Add to `package.json` as:

```json
{
    "prettier": "@crgeary/configuration-prettier"
}
```

Or extend in `prettier.config.js` with:

```js
module.exports = {
    ...require('@crgeary/configuration-prettier'),
};
```
