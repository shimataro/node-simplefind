# node-simplefind

[![Build Status (Linux)][image-build-linux]][link-build-linux]
[![Code Coverage][image-code-coverage]][link-code-coverage]
[![Release][image-release]][link-release]
[![Node.js version][image-engine]][link-engine]
[![License][image-license]][link-license]

simple 'find' implementation and some more useful options

## Install

```bash
npm i -D node-simplefind
```

## Examples

### optimize multiple SVG files using [svgo](https://www.npmjs.com/package/svgo)

`package.json`:

```json
{
  "scripts": {
    "build": "node-simplefind src -name '*.svg' -exec svgo -i {} -o dist/{r=src} \\;"
  }
}
```

[image-build-linux]: https://github.com/shimataro/node-simplefind/workflows/Linux/badge.svg
[link-build-linux]: https://github.com/shimataro/node-simplefind/actions?query=workflow%3ALinux
[image-code-coverage]: https://img.shields.io/codecov/c/github/shimataro/node-simplefind/master.svg
[link-code-coverage]: https://codecov.io/gh/shimataro/node-simplefind
[image-release]: https://img.shields.io/github/release/shimataro/node-simplefind.svg
[link-release]: https://github.com/shimataro/node-simplefind/releases
[image-engine]: https://img.shields.io/node/v/node-simplefind.svg
[link-engine]: https://nodejs.org/
[image-license]: https://img.shields.io/github/license/shimataro/node-simplefind.svg
[link-license]: ./LICENSE
