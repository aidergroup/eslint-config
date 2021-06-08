# @aider/eslint-config

[![publish](https://github.com/aidergroup/eslint-config-aider/actions/workflows/npm-publish.yml/badge.svg)](https://github.com/aidergroup/eslint-config-aider/actions/workflows/npm-publish.yml)

## Installation

```sh
$ npm i -D @aider/eslint-config
```

Create a `.eslintrc.js` in project root:

```
module.exports = {
  extends: ['@aider'],
}
```

## Publishing

```sh
$ npm run release -- --release-as {major|minor|patch}
$ git push --follow-tags origin main
```
