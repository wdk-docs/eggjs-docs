---
title: "axios"
linkTitle: ""
weight: 1
---

[![npm version](https://img.shields.io/npm/v/axios.svg?style=flat-square)](https://www.npmjs.org/package/axios)
[![CDNJS](https://img.shields.io/cdnjs/v/axios.svg?style=flat-square)](https://cdnjs.com/libraries/axios)
![Build status](https://github.com/axios/axios/actions/workflows/ci.yml/badge.svg)
[![Gitpod Ready-to-Code](https://img.shields.io/badge/Gitpod-Ready--to--Code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/axios/axios)
[![code coverage](https://img.shields.io/coveralls/mzabriskie/axios.svg?style=flat-square)](https://coveralls.io/r/mzabriskie/axios)
[![install size](https://packagephobia.now.sh/badge?p=axios)](https://packagephobia.now.sh/result?p=axios)
[![npm downloads](https://img.shields.io/npm/dm/axios.svg?style=flat-square)](http://npm-stat.com/charts.html?package=axios)
[![gitter chat](https://img.shields.io/gitter/room/mzabriskie/axios.svg?style=flat-square)](https://gitter.im/mzabriskie/axios)
[![code helpers](https://www.codetriage.com/axios/axios/badges/users.svg)](https://www.codetriage.com/axios/axios)

Promise based HTTP client for the browser and node.js

> New axios docs website: [click here](https://axios-http.com/)

## Table of Contents

- [Features](#features)
- [Browser Support](#browser-support)
- [Installing](#installing)
- [Example](#example)
- [Axios API](#axios-api)
- [Request method aliases](#request-method-aliases)
- [Concurrency (Deprecated)](#concurrency-deprecated)
- [Creating an instance](#creating-an-instance)
- [Instance methods](#instance-methods)
- [Request Config](#request-config)
- [Response Schema](#response-schema)
- [Config Defaults](#config-defaults)
  - [Global axios defaults](#global-axios-defaults)
  - [Custom instance defaults](#custom-instance-defaults)
  - [Config order of precedence](#config-order-of-precedence)
- [Interceptors](#interceptors)
- [Handling Errors](#handling-errors)
- [Cancellation](#cancellation)
- [Using application/x-www-form-urlencoded format](#using-applicationx-www-form-urlencoded-format)
  - [Browser](#browser)
  - [Node.js](#nodejs)
    - [Query string](#query-string)
    - [Form data](#form-data)
- [Semver](#semver)
- [Promises](#promises)
- [TypeScript](#typescript)
- [Resources](#resources)
- [Credits](#credits)
- [License](#license)

## Browser Support

| ![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) |
| ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| Latest ✔                                                                                 | Latest ✔                                                                                    | Latest ✔                                                                                 | Latest ✔                                                                              | Latest ✔                                                                           | 11 ✔                                                                                                                         |

[![Browser Matrix](https://saucelabs.com/open_sauce/build_matrix/axios.svg)](https://saucelabs.com/u/axios)

## Gitpod

You can use Gitpod an online IDE(which is free for Open Source) for contributing or running the examples online.

[![Open in Gitpod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/axios/axios/blob/master/examples/server.js)

## Semver

Until axios reaches a `1.0` release, breaking changes will be released with a new minor version. For example `0.5.1`, and `0.5.4` will have the same API, but `0.6.0` will have breaking changes.

## Resources

- [Changelog](https://github.com/axios/axios/blob/master/CHANGELOG.md)
- [Upgrade Guide](https://github.com/axios/axios/blob/master/UPGRADE_GUIDE.md)
- [Ecosystem](https://github.com/axios/axios/blob/master/ECOSYSTEM.md)
- [Contributing Guide](https://github.com/axios/axios/blob/master/CONTRIBUTING.md)
- [Code of Conduct](https://github.com/axios/axios/blob/master/CODE_OF_CONDUCT.md)

## Credits

axios is heavily inspired by the [$http service](https://docs.angularjs.org/api/ng/service/$http) provided in [AngularJS](https://angularjs.org/). Ultimately axios is an effort to provide a standalone `$http`-like service for use outside of AngularJS.

## License

[MIT](LICENSE)
