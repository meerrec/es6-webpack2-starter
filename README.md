[![Board Status](https://meerrec.visualstudio.com/55c15bf0-052a-45af-8f28-ed7d05194a06/c8d2ce08-2bf3-4cb1-8489-6fd7431661c3/_apis/work/boardbadge/177b5027-471d-4c8c-8c66-871a8810f9f6)](https://meerrec.visualstudio.com/55c15bf0-052a-45af-8f28-ed7d05194a06/_boards/board/t/c8d2ce08-2bf3-4cb1-8489-6fd7431661c3/Microsoft.RequirementCategory)
# es6-webpack2-starter

[![npm](https://img.shields.io/npm/v/es6-webpack2-starter.svg?maxAge=2592000?style=flat-square)](https://www.npmjs.com/package/es6-webpack2-starter)
[![npm](https://img.shields.io/npm/l/es6-webpack2-starter.svg?maxAge=2592000?style=flat-square)](https://github.com/micooz/es6-webpack2-starter/blob/master/LICENSE)
[![David](https://img.shields.io/david/micooz/es6-webpack2-starter.svg?maxAge=2592000?style=flat-square)]()
[![David](https://img.shields.io/david/dev/micooz/es6-webpack2-starter.svg?maxAge=2592000?style=flat-square)]()
[![%e2%9d%a4](https://img.shields.io/badge/made%20with-%e2%9d%a4-ff69b4.svg?style=flat-square)](https://apporz.com)

> A template project for ECMAScript(latest), webpack3, sass and postcss.

## Features

* es6: by babel and it's presets and plugins
* css module: by css-loader
* sass: by sass-loader
* webpack3 provides faster compilation
* auto-reload by webpack-dev-server

## Installation

    $ npm install
    # or
    $ yarn install

## Configuration

1. Copy then rename `env.example.js` to `env.js` if it is not done automatically by `postinstall`.

You can custom your local environment via `env.js`, so that it does not affect others.

## Run in development

    $ npm start

## Build for production

    $ npm run build

This will generator minified css and scripts to `dist/`.

## Proxy

You can change your proxy rules in `proxy/rules`.

## Need Help?

Ask questions [here](https://github.com/micooz/es6-webpack2-starter/issues).

## Any advise?

PR welcome [here](https://github.com/micooz/es6-webpack2-starter/pulls).

## Contributors

Micooz <micooz@hotmail.com>

## License

MIT
