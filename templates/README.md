# [Start Bootstrap - Creative](https://startbootstrap.com/template-overviews/creative/)

[Creative](http://startbootstrap.com/template-overviews/creative/) is a one page creative theme for [Bootstrap](http://getbootstrap.com/) created by [Start Bootstrap](http://startbootstrap.com/).

## Preview

[![Creative Preview](https://startbootstrap.com/assets/img/screenshots/themes/creative.png)](https://blackrockdigital.github.io/startbootstrap-creative/)

**[View Live Preview](https://blackrockdigital.github.io/startbootstrap-creative/)**

## Status

[![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/BlackrockDigital/startbootstrap-creative/master/LICENSE)
[![npm version](https://img.shields.io/npm/v/startbootstrap-creative.svg)](https://www.npmjs.com/package/startbootstrap-creative)
[![Build Status](https://travis-ci.org/BlackrockDigital/startbootstrap-creative.svg?branch=master)](https://travis-ci.org/BlackrockDigital/startbootstrap-creative)
[![dependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-creative/status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-creative)
[![devDependencies Status](https://david-dm.org/BlackrockDigital/startbootstrap-creative/dev-status.svg)](https://david-dm.org/BlackrockDigital/startbootstrap-creative?type=dev)

## Download and Installation

To begin using this template, choose one of the following options to get started:
* [Download the latest release on Start Bootstrap](https://startbootstrap.com/template-overviews/creative/)
* Install via npm: `npm i startbootstrap-creative`
* Clone the repo: `git clone https://github.com/BlackrockDigital/startbootstrap-creative.git`
* [Fork, Clone, or Download on GitHub](https://github.com/BlackrockDigital/startbootstrap-creative)

## Usage

### Basic Usage

After downloading, simply edit the HTML and CSS files included with the template in your favorite text editor to make changes. These are the only files you need to worry about, you can ignore everything else! To preview the changes you make to the code, you can open the `index.html` file in your web browser.

### Advanced Usage

> **2026-08-19 變更：Gulp 建置工具鏈已移除。**
>
> 原本的 `package.json`、`package-lock.json`、`gulpfile.js`、`.travis.yml`、
> `.browserslistrc` 已從本 repo 刪除，原因有二：
>
> 1. **已經無法運作。** 工具鏈鎖定 `node-sass@4.12.0`，該版本最高只支援
>    Node 12；在現行 Node 環境下 `npm install` 會直接失敗，等於這套建置
>    早已是死碼。
> 2. **是全部資安警示的來源。** lockfile 共 529 個套件，其中 524 個是
>    `dev` 相依（gulp 4 / node-sass 4 / browser-sync 2.26 等 2019 年版本），
>    GitHub Dependabot 因此回報 95 個漏洞。這些套件從未出貨到瀏覽器，
>    卻讓真正需要注意的前台問題被淹沒。
>
> **網站運作不受影響。** 前台載入的是已編譯好的 `css/creative.min.css`、
> `js/creative.min.js` 與 `vendor/` 下的資產（見 `theme.tpl`），與 Node
> 建置無關。
>
> **若日後需要重新編譯 `scss/`：** `scss/` 原始檔仍保留在 repo 中。建議
> 改用現行的 Dart Sass CLI，例如
> `npx sass scss/creative.scss css/creative.css --style=compressed`，
> 不要復原舊工具鏈。舊檔案若真的需要，可從 git 歷史取回
> （`git show <本次 commit>^:templates/gulpfile.js`）。

## Bugs and Issues

Have a bug or an issue with this template? [Open a new issue](https://github.com/BlackrockDigital/startbootstrap-creative/issues) here on GitHub or leave a comment on the [template overview page at Start Bootstrap](http://startbootstrap.com/template-overviews/creative/).

## About

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* https://startbootstrap.com
* https://twitter.com/SBootstrap

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* http://davidmiller.io
* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-creative/blob/gh-pages/LICENSE) license.
