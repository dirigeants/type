<div align="center">

![Sapphire Logo](https://cdn.skyra.pw/gh-assets/sapphire-banner.png)

# @sapphire/type

**A type detection utility for JavaScript.**

[![GitHub](https://img.shields.io/github/license/sapphire-community/utilities)](https://github.com/sapphire-community/utilities/blob/main/LICENSE.md)
[![Total alerts](https://img.shields.io/lgtm/alerts/g/sapphire-community/utilities.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/sapphire-community/utilities/alerts/)
[![Language grade: JavaScript/TypeScript](https://img.shields.io/lgtm/grade/javascript/g/sapphire-community/utilities.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/sapphire-community/utilities/context:javascript)
[![Coverage Status](https://coveralls.io/repos/github/sapphire-community/utilities/badge.svg?branch=main)](https://coveralls.io/github/sapphire-community/utilities?branch=main)
[![npm bundle size](https://img.shields.io/bundlephobia/min/@sapphire/type?logo=webpack&style=flat-square)](https://bundlephobia.com/result?p=@sapphire/type)
[![npm](https://img.shields.io/npm/v/@sapphire/type?color=crimson&logo=npm&style=flat-square)](https://www.npmjs.com/package/@sapphire/type)
[![Depfu](https://badges.depfu.com/badges/ec42ff3d6bae55eee1de4749960852b3/count.svg)](https://depfu.com/github/sapphire-community/utilities?project_id=15195)

</div>

**Table of Contents**

-   [Description](#description)
-   [Features](#features)
-   [Installation](#installation)
-   [Usage](#usage)
    -   [Basic Usage](#basic-usage)
-   [API Documentation](#api-documentation)
-   [Buy us some doughnuts](#buy-us-some-doughnuts)
-   [Contributors ✨](#contributors-%E2%9C%A8)

## Description

Sometimes there is a need to know what a value's type of something is, this package exists to satisfy those needs by implementing a parser that can retrieve the type of the value recursively and process a string similar to TypeScript's types.

## Features

-   Written in TypeScript
-   Bundled with Rollup so it can be used in NodeJS and browsers
-   Offers CommonJS, ESM and UMD bundles
-   Fully tested

## Installation

```sh
yarn add @sapphire/type
# npm install @sapphire/type
```

## Usage

**Note:** While this section uses `require`, the imports match 1:1 with ESM imports. For example `const { Type } = require('@sapphire/type')` equals `import { Type } from '@sapphire/type'`.

**Note:** When using ESM syntax you can also default-import `Type` class: `import Type from '@sapphire/type'`.

**Note:** The internal functions of `getPromiseDetails` and `getProxyDetails` are also exported. If you don't know what these are, then you need not be concerned about this.

### Basic Usage

```ts
// Import the Type class
const { Type } = require('@sapphire/type');

// Define a Type with an array of two numbers
const type = new Type([1, 2]);

console.log(type.toString());
// Logs: Array<number>
```

---

## API Documentation

For the full API documentation please refer to the TypeDoc generated [documentation](https://sapphire-community.github.io/utilities/modules/_sapphire_type.html).

## Buy us some doughnuts

Sapphire Community is and always will be open source, even if we don't get donations. That being said, we know there are amazing people who may still want to donate just to show their appreciation. Thank you very much in advance!

We accept donations through Open Collective, Ko-fi, PayPal, Patreon and GitHub Sponsorships. You can use the buttons below to donate through your method of choice.

|   Donate With   |                       Address                       |
| :-------------: | :-------------------------------------------------: |
| Open Collective | [Click Here](https://sapphirejs.com/opencollective) |
|      Ko-fi      |      [Click Here](https://sapphirejs.com/kofi)      |
|     Patreon     |    [Click Here](https://sapphirejs.com/patreon)     |
|     PayPal      |     [Click Here](https://sapphirejs.com/paypal)     |

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://favware.tech/"><img src="https://avatars.githubusercontent.com/u/4019718?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Jeroen Claassens</b></sub></a><br /><a href="https://github.com/sapphire-community/type/commits?author=Favna" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/PyroTechniac"><img src="https://avatars.githubusercontent.com/u/39341355?v=4?s=100" width="100px;" alt=""/><br /><sub><b>Gryffon Bellish</b></sub></a><br /><a href="https://github.com/sapphire-community/type/commits?author=PyroTechniac" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
