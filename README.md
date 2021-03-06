# React China new Forum Frontend

[![Gitter chat][gitter-image]][gitter-url] [![GitHub license][license-image]][license-url]

----

> React 中文社区 React.js 版前端界面

## 状态

> 正在初始化项目

## 计划

* 完成 JSX 基本开发框架
* 梳理 Discourse API
* 制定 Actions, Store, Router 规范
* 完成顶层组件
* 组件细化

## Develop

```text
npm i
```

You need a static file server for the HTML files. Personally I suggest using Nginx.

Develop:

```bash
gulp html # regenerate index.html
webpack-dev-server --hot # enable live-reloading
```

Build (Pack and optimize js, reivision js and add entry in `index.html`):

```bash
gulp build
```

## Contribution

- If you want to discuss something or just need help, here is our [gitter.im room](https://gitter.im/react-china/forum-frontend).
- Have an idea? Found a bug? See [how to contribute][contributing-url].

## License

MIT (http://www.opensource.org/licenses/mit-license.php)

[gitter-url]: https://gitter.im/react-china/forum-frontend
[gitter-image]: https://badges.gitter.im/Join%20Chat.svg
[license-image]: https://img.shields.io/github/license/mashape/apistatus.svg
[license-url]: http://www.opensource.org/licenses/mit-license.php
[contributing-url]: /CONTRIBUTING.md
