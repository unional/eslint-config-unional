# eslint-config-unional

[![NPM version][npm-image]][npm-url]
[![NPM downloads][downloads-image]][downloads-url]
[![Build status][travis-image]][travis-url]

[![Greenkeeper badge][green-keeper-image]][green-keeper-url]
[![semantic-release][semantic-release-image]][semantic-release-url]

[![Visual Studio Code][vscode-image]][vscode-url]

A [`eslint`](https://eslint.org/) config package with several styles to choose from.

## Design Principles

There are several configurations available in this package.
Although they are different as they are designed for different programers,
here are the principles that they all follows:

- They are designed to be used by team
- Each team member can use their own IDE of choice
- The formatter available on each IDE should work with each configuration
- Code should look well and consistent on each IDE with folding
  - so that when you stop by your team member's cube, the code looks the same.
  - i.e., unfortunately, no [tab]
- Thrive for easy to write (with fewest keystrokes) while keeping the code clean

## Usage

```sh
# Install
npm install eslint-config-unional
```

```js
// .eslint.json
{
  "extends": "unional" // or other styles
}
```

## Npm Commands

There are a few useful commands you can use during development.

```sh
# Run tests to validate the rules are checked correctly.
npm test
```

[npm-image]: https://img.shields.io/npm/v/eslint-config-unional.svg?style=flat
[npm-url]: https://npmjs.org/package/eslint-config-unional
[downloads-image]: https://img.shields.io/npm/dm/eslint-config-unional.svg?style=flat
[downloads-url]: https://npmjs.org/package/eslint-config-unional
[travis-image]: https://img.shields.io/travis/unional/eslint-config-unional/master.svg?style=flat
[travis-url]: https://travis-ci.org/unional/eslint-config-unional?branch=master
[green-keeper-image]:
https://badges.greenkeeper.io/unional/eslint-config-unional.svg
[green-keeper-url]:https://greenkeeper.io/
[semantic-release-image]:https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg
[semantic-release-url]:https://github.com/semantic-release/semantic-release
[vscode-image]:https://img.shields.io/badge/vscode-ready-green.svg
[vscode-url]:https://code.visualstudio.com/