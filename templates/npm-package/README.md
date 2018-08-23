npm-package
===========

## Introduction

Needs introduction

### Features

 - One
 - Two
 - Three

## Install

```bash
npm install npm-package
```

## Use

### Code Example

```javascript
import npm-package from 'npm-package';

```

### More examples

You'll find the [example](/contd/npm-package/tree/master/example/) folder wich contains basic examples.

## Api

## Contributers

#### Install

```shell
git clone https://github.com/topheman/lite-router.git
cd lite-router
yarn
```

Install, then eventually, `npm link` the library to use it in local.

In your own project where you want to locally test `lite-router`, just run `npm link lite-router`.

#### Build

* One shot
 * all formats: `npm run build`
 * commonjs (output in `lib` dir): `npm run build:commonjs`
 * ecmascript module (ouput in `es` dir): `npm run build:es`
 * umd (output as `dist/lite-router.js`) : `npm run build:umd`
 * umd - minified (output as `dist/lite-router.min.js`) : `npm run build:umd:min`
* Watch mode:
 * commonjs: `npm run build:watch` or `npm run build:commonjs:watch`
 * umd: `npm run build:umd:watch`
 * es: `npm run build:es:watch`

#### Test

 * One shot: `npm test` (will also lint the source code)
 * Only unit tests: `npm run jest`
 * Watch mode: `npm run jest:watch`

The tests are in the `tests` folder, it is ran via [jest](https://facebook.github.io/jest/).

#### Publish

##### Publish npm package

```shell
npm run build
npm publish
```

Copyright 2017 © Jason Kumpf

> Permission is hereby granted, free of charge, to any person obtaining a copy of this software
> and associated documentation files (the "Software"), to deal in the Software without
> restriction, including without limitation the rights to use, copy, modify, merge, publish,
> distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the
> Software is furnished to do so, subject to the following conditions:
> The above copyright notice and this permission notice shall be included in all copies or
> substantial portions of the Software.
> The Software is provided "as is", without warranty of any kind, express or implied, including
> but not limited to the warranties of merchantability, fitness for a particular purpose and
> noninfringement. In no event shall the authors or copyright holders be liable for any claim,
> damages or other liability, whether in an action of contract, tort or otherwise, arising from,
> out of or in connection with the software or the use or other dealings in the Software.
