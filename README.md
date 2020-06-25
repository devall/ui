<p align="center">
  <img width="auto" src="public/bg.png">
  <br />
  Devall design system for React
  <br /><br />
  <a href="https://github.com/devall/ui/actions?query=workflow%3Abuild-storybook">
    <img src="https://img.shields.io/github/workflow/status/devall/ui/build-storybook/master" />
  </a>&nbsp;&nbsp;
  <a href="https://npm.im/@devall/ui">
    <img src="https://img.shields.io/npm/v/@devall/ui.svg" />
  </a>&nbsp;&nbsp;
  <a href="https://npm.im/@devall/ui">
    <img src="https://img.shields.io/npm/dw/@devall/ui" />
  </a>&nbsp;&nbsp;
  <a href="https://github.com/devall/ui/blob/master/LICENSE">
    <img src="https://img.shields.io/npm/l/@devall/ui" />
  </a>&nbsp;&nbsp;
  <a href="https://bundlephobia.com/result?p=@devall/ui">
    <img src="https://img.shields.io/bundlephobia/minzip/@devall/ui" />
  </a>
  <a href="https://github.com/devall/ui">
    <img alt="GitHub stars" src="https://img.shields.io/github/stars/devall/ui?style=social" />
  </a>
</p>

[![NPM](https://img.shields.io/npm/v/@eduzz/houston.svg)](https://www.npmjs.com/package/@eduzz/houston) [![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

## Tech stack

Building components

- 📚 [Storybook](https://storybook.js.org/) for UI component development and [auto-generated docs](https://medium.com/Storybookjs/Storybook-docs-sneak-peak-5be78445094a)
- 💅 [Styled-components](https://styled-components.com/) for component-scoped styling
- ⚛️ [React](https://reactjs.org/) declarative component-centric UI

Maintaining the system

- 📦 [NPM](https://www.npmjs.com/) for [packaging and distribution](https://blog.hichroma.com/how-packaging-makes-it-dead-simple-to-share-ui-components-29912593539d)
- 🚥 [Github Actions](https://github.com/features/actions) Continuous integration

## 📦 Install

To use reaviz in your project, install it via npm/yarn:

```
npm i @devall/ui --save
```

or

```
yarn add @devall/ui
```

## 🔭 Development

If you want to run REAVIZ locally, its super easy!

- Clone the repository
- `yarn install`
- `yarn start`
- Browser opens to Storybook page

to publish the repo to git you can run:

- `yarn version --new-version x.x.x` to bump the version
- `git push --follow-tags`
