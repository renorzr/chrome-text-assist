<div align="center">
<img src="public/icon-128.png" alt="logo"/>
<h1> Chrome Extension Boilerplate with<br/>React + Vite + TypeScript</h1>

![](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![](https://img.shields.io/badge/Typescript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![](https://badges.aleen42.com/src/vitejs.svg)
![GitHub action badge](https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite/actions/workflows/build-zip.yml/badge.svg)
<img src="https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https://github.com/Jonghakseo/chrome-extension-boilerplate-react-viteFactions&count_bg=%23#222222&title_bg=%23#454545&title=😀&edge_flat=true" alt="hits"/>

> This project is listed in the [Awesome Vite](https://github.com/vitejs/awesome-vite)

</div>

# 功能

## 翻译

可以设置用户语言和第二语言，自动在识别用户选择的语言并翻译为用户语言。当选中的语言是用户语言时，自动翻译为第二语言。

## 补全

用户选择，或热键呼出，根据用户选中的文字，展开联想，补全文字。支持 Tab 键快速补全。

## 概括

对用户选中的文字进行要点概括。

## 扩写

对用户选中的文字进行扩写。

## 润色

对用户选中的文字进行润色。

## Table of Contents

- [Intro](#intro)
- [Features](#features)
- [Installation](#installation)
  - [Procedures](#procedures)
- [Screenshots](#screenshots)
  - [NewTab](#newtab)
  - [Popup](#popup)
- [Sample](#sample)
- [Documents](#documents)

## Intro <a name="intro"></a>

This boilerplate is made for creating chrome extensions using React and Typescript.

> The focus was on improving the build speed and development experience with Vite.

## Features <a name="features"></a>

- [React 18](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io/)
- [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
- [Vite](https://vitejs.dev/)
- [SASS](https://sass-lang.com/)
- [ESLint](https://eslint.org/)
- [Prettier](https://prettier.io/)
- [Chrome Extension Manifest Version 3](https://developer.chrome.com/docs/extensions/mv3/intro/)
- HRR(Hot Rebuild & Refresh/Reload)

## Installation <a name="installation"></a>

### Procedures <a name="procedures"></a>

1. Clone this repository.
2. Change `name` and `description` in package.json => **Auto synchronize with manifest**
3. Run `yarn install` or `npm i` (check your node version >= 16.6, recommended >= 18)
4. Run `yarn dev` or `npm run dev`
5. Load Extension on Chrome
   1. Open - Chrome browser
   2. Access - chrome://extensions
   3. Check - Developer mode
   4. Find - Load unpacked extension
   5. Select - `dist` folder in this project (after dev or build)
6. If you want to build in production, Just run `yarn build` or `npm run build`.

## Screenshots <a name="screenshots"></a>

### New Tab <a name="newtab"></a>

<img width="971" src="https://user-images.githubusercontent.com/53500778/162631646-cd40976b-b737-43d0-8e6a-6ac090a2e2d4.png">

### Popup <a name="popup"></a>

<img width="314" alt="popup" src="https://user-images.githubusercontent.com/53500778/203561728-23517d46-12e3-4139-8a4f-e0b2f22a6ab3.png">

## Sample <a name="sample"></a>

- https://github.com/Jonghakseo/drag-gpt-extension
- https://github.com/Jonghakseo/pr-commit-noti

## Documents <a name="documents"></a>

- [Vite Plugin](https://vitejs.dev/guide/api-plugin.html)
- [ChromeExtension](https://developer.chrome.com/docs/extensions/mv3/)
- [Rollup](https://rollupjs.org/guide/en/)
- [Rollup-plugin-chrome-extension](https://www.extend-chrome.dev/rollup-plugin)

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=Jonghakseo/chrome-extension-boilerplate-react-vite&type=Date)](https://star-history.com/#Jonghakseo/chrome-extension-boilerplate-react-vite&Date)

---

## Thanks To

| [Jetbrains](https://jb.gg/OpenSourceSupport)                                                                                               | [Jackson Hong](https://www.linkedin.com/in/j-acks0n/)                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------------------ |
| <img width="100" src="https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.png" alt="JetBrains Logo (Main) logo."> | <img width="100" src='https://avatars.githubusercontent.com/u/23139754?v=4' alt='Jackson Hong'/> |

---

[Jonghakseo](https://nookpi.tistory.com/)
