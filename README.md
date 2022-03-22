<!--
 * @Author: your name
 * @Date: 2022-03-22 15:45:14
 * @LastEditTime: 2022-03-22 17:23:41
 * @LastEditors: Please set LastEditors
 * @Description: 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%
 * @FilePath: /admin/README.md
-->

# 管理后台搭建

本项目基于：https://github.com/GeekQiaQia/vue3.0-template-admin

# 技术相关

### 搭建

vue3+ts+vite

### 编辑器

vscode+vetur,并且 "vetur.experimental.templateInterpolationService": true,

- script setup 目前是处于 RFC 阶段，要获得对语法的适当 IDE 支持，请使用 volar 而不是 vetur(禁用)

### 工程化

- Git Hook 工具：[husky](https://typicode.github.io/husky/#/) + [lint-staged](https://github.com/okonet/lint-staged)

- 代码规范：[EditorConfig](http://editorconfig.org) + [Prettier](https://prettier.io/) + [ESLint](https://eslint.org/) + [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript#translation)

- 提交规范：[Commitizen](http://commitizen.github.io/cz-cli/) + [Commitlint](https://commitlint.js.org/#/)

### 使用到的插件/库

- **eslint-plugin-vue** [eslint-plugin-vue](https://eslint.vuejs.org/user-guide/#faq)vue 官方 eslint 插件 这个插件允许我们使用 eslint 检查<template>和<script>,以及文件中的 vue 代码
- **axios** 强大的前端请求库
- **fues.js** [fues.js Fuzzy Search 前端模糊搜索](https://github.com/krisk/Fuse) 小型和中等数据进行前端模糊筛选
- **echart** [echart 数据可视化](http://echarts.apache.org/zh/index.html)
- **antv** [antv 蚂蚁数据可视化](https://antv.vision/zh)
- **xlsx** [xlsx SheetJS ](https://www.npmjs.com/package/xlsx)
- **jszip** [jszip 优秀的前端压缩库 ](https://github.com/Stuk/jszip)
- **mockjs** [mockjs 模拟和交互数据](http://mockjs.com/)
- **wangeditor** [wangeditor 富文本编辑器](https://www.wangeditor.com/doc/)
- **fullcalendar** [fullcalendar 丰富的日历插件](https://github.com/fullcalendar/fullcalendar-example-projects/tree/master/vue3-typescript)

### 功能

- [x] Element Plus
- [x] N+1 多级菜单
- [x] Dashboard
- [x] 表格
- [x] router Tab 选项卡
- [x] 表单
- [x] 图表 :antv or echart
- [x] 二维码生成
- [x] 导入导出 Excel
- [x] 导出 Zip 文件
- [x] 拖拽组件
- [x] 富文本编辑器
- [x] markdown 编辑器
- [x] 个人页
- [x] 登录/注册页
- [x] 404 / 403
- [x] 菜单管理
- [x] 角色管理
- [x] 自定义图标
- [x] 图片拖拽/裁剪
- [x] 支持切换主题色:一键换肤
- [x] 指令权限：v-permisson /全局方法：$permission (参考 tableList.vue)
- [x] 国际化
- [x] 项目看板
- [x] 可拖拽弹窗
- [x] 导航模式切换
- [x] 内容区域控制
- [x] 重构 request.ts 请求，使其灵活可配置化；
- [x] 使用 AES 加密方式，对密码进行安全加密；
- [x] 完成换肤切换功能，使用 ElementPlus theme-chalk 实现换肤
- [x] 重构登录注册页面，完善忘记密码交互以及必填字段校验
- [x] 设计角色管理，选择不同的角色，授权不同的菜单
- [x] 根据不同的登录用户角色，展示不同的菜单
- [x] 【enhance】 vite 不同环境变量配置