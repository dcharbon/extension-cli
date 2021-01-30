# Extension CLI

[![npm](https://img.shields.io/npm/v/extension-cli?style=flat-square)](https://www.npmjs.com/package/extension-cli)
[![travis](https://img.shields.io/travis/mobilefirstllc/extension-cli?style=flat-square)](https://travis-ci.com/github/MobileFirstLLC/extension-cli)
[![Code Climate maintainability](https://img.shields.io/codeclimate/maintainability/MobileFirstLLC/extension-cli?style=flat-square)](https://codeclimate.com/github/MobileFirstLLC/extension-cli/maintainability)
![Last commit](https://img.shields.io/github/last-commit/mobilefirstllc/extension-cli?style=flat-square)
<!-- [![Coveralls github](https://img.shields.io/coveralls/github/MobileFirstLLC/extension-cli?style=flat-square)](https://coveralls.io/github/MobileFirstLLC/extension-cli) hide coverage because it represents only utilities and may signal incorrectly; add back when this includes all of CLI commands -->

**Extension CLI is a command-line application that facilitates chromium&#8727;-based extension development by providing
a systematic way to build, test and document extension projects. It handles the project setup and builds and lets you focus 
on the extension you are creating.**

* * *

## Features

-  🖥️ &nbsp; **Javascript Bundling** — Compiles, bundles and minifies javascript files (supports [ES6 syntax](http://es6-features.org/)) <br/>

-  🎨 &nbsp; **CSS Bundling** — Compiles, bundles, and minifies CSS and [SASS](https://sass-lang.com/guide) files <br/>

-  🔧 &nbsp; **Linting** — lint JavaScript using [ESLint](https://eslint.org/) <br/>

-  📦 &nbsp; **ZIP Generation** — Generates a `.zip` file for uploading to extension marketplace ([Chrome Web Store](https://chrome.google.com/webstore/category/extensions) etc.) <br/>

-  📝 &nbsp; **Document Source Code** — Generates code documentation using [JSDoc](https://jsdoc.app/about-getting-started.html) <br/>

-  ⚗️ &nbsp; **Unit Testing** —  Sets up a unit testing environment with [mocha](https://mochajs.org), [chai](https://www.chaijs.com/), [sinon-chrome](https://github.com/acvetkov/sinon-chrome), and [js-dom](https://github.com/rstacruz/jsdom-global) <br/>

-  ⚔️ &nbsp; **Cross-Browser Compatibility** - create extensions for Chrome, Edge, Firefox or Opera. <br/>

![feature image](https://raw.githubusercontent.com/MobileFirstLLC/extension-cli/master/.github/feature.png)

## Getting Started

**Note:** Using this CLI assumes you have Node.js installed. If you do not, you can [install it here](https://nodejs.org/en/download/).

##### Create new extension project

```text
npx extension-cli
```

##### Add to an existing project

```text
npm install extension-cli
```

### Commands Reference

Command | Description
--- | ---
**xt-build** | Run builds; env flags: `-e prod` and `-e dev`
**xt-test**| Run unit tests
**xt-docs**| Generate docs
**xt-sync**| Update project config files to match the latest defaults supplied by this CLI
**xt-clean** | Remove automatically generated files

* * *

## Read the Docs

<img align="left" width="64" src="https://raw.githubusercontent.com/MobileFirstLLC/extension-cli/master/guide/assets/images/guide.svg" alt="" /> &nbsp; 
<br/>&nbsp; &nbsp;<strong><a href="https://oss.mobilefirst.me/extension-cli/">User Guide →</a></strong><br/><br/>

### CLI Developer Guide

If you are interested in extending this project or forking **[see this guide &rarr;](https://oss.mobilefirst.me/extension-cli/13-cli-development/)**

* * *

## Motivation

After developing multiple browser extensions, it became clear that there were several steps in the development process that stayed the same between every project. 

Instead of setting up these tasks individually for each project, it made more sense to combine everything in a utility tool that could be shared between projects. 

This approach helps with creating a common, consistent development approach between multiple projects, reduces time to get started, and makes it easier to update build tools and scripts across multiple projects as many npm packages inevitably need to be updated (frequently!).

* * *

**Issues & Feature Requests:** [Submit on Github](https://github.com/MobileFirstLLC/extension-cli/issues/new/choose)

**Maker:** [Mobile First](https://mobilefirst.me) &nbsp;  [![Twitter Follow](https://img.shields.io/twitter/follow/mobilefirstllc?label=follow&style=social)](https://twitter.com/intent/follow?screen_name=mobilefirstllc&tw_p=followbutton)

**License:** [MIT](https://github.com/MobileFirstLLC/extension-cli/blob/master/LICENSE)
