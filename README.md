# SUI

> Security-UI Framework

## Feature

- 基于 Antd 二次封装的 React UI 组件框架
- 提供通用上层组件与模版、种子工程与脚手架、icon 图标库等
- 适用于中后台项目快速搭建，开箱即用

## 文档地址

- [官网文档](http://43.138.105.171/sui/#/guides/about)

## 使用（详见官方文档）

- 安装：

  `npm install sui-components`

- 使用：

  ```javascript
  import { Wrapper, Logo, Menu, RouterPage, Avatar } from 'sui-components';
  ```

## 目录结构

- src/core 核心组件库
- src/styles 样式库
- src/docs 组件文档
- src/pages demo 示例
- src/menu.config.js 菜单配置
- src/routerPage.config.js 页面路由配置
- src/app.js 入口 js 文件

## 发布

- 提交 merge request 进行代码 review
- 使用 [sui-components](https://github.com/tangzhirong/sui-components.git) 发版，规范版本号规则

## TODO

- ~~修改 webpack production config~~
- ~~菜单和面包屑集成~~
- ~~表单组件 inline 布局优化~~
- ~~多表单校检~~
- ~~表单渲染层抽象~~
- dream-builder 可视化搭建接入

## 其它

- npm 发布仓库：[sui-components](https://github.com/tangzhirong/sui-components.git)
- 图标库： [sui-icon](https://github.com/tangzhirong/sui-icons.git)
- 种子工程：[sui-seed]()

## ISSUE

- 使用问题欢迎提 issue [反馈地址](https://github.com/tangzhirong/sui-core/issues)
