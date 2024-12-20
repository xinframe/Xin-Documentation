---
order: 1
title: 介绍
---

<h1 style="text-align: center;font-size: 60px">Xin Admin 全栈开发框架</h1>

:::success{title='Apache License' }
遵循 Apache License 无需授权即可免费商用
:::

## ✨ 介绍

XinAdmin 是一个中后台开发框架，基于 PHP8 + React + TypeScript + UmiJs + Ant Design 等技术栈，
拥有权限验证、用户分组、Swagger 文档、数据字典、系统设置、文件系统、可视化 CRUD 等便捷开发功能，
提供 Taro 多端小程序 解决方案。不仅可以让开发者体验到技术带来的便捷，提升自己技术栈，而且可以使开发者专注业务，减少重复代码的编写，节省时间。
项目遵循 Apache License 无需授权即可免费商用。

<img src="https://file.xinadmin.cn/file/demo.png"/>

## 主要特征

### 🚀 Online 在线开发

在线开发页面，支持一键生成 CRUD 代码，一键生成控制器、模型、验证器以及前端页面，新增或编辑字段实时更新效果，预览效果，提供多种表单组件，支持 Mock 模拟数据。

### 🧩 Swagger 文档

基于 Swagger PHP 支持注解文档生成，搭配 UmiJs 前端可实现 0 接口 0 类型定义，一键生成 api 接口文件与 Ts 类型文件

### 📟 权限控制系统

我们提供了完善的权限验证系统，支持客户端、管理端，双动态菜单，权限路由菜单、页面按钮级权限控制，不再为路由的配置烦恼，使用 PHP8 注解验证精确控制接口请求。

### ♻️ 数据字典和全局设置

强大的数据字典，支持 CRUD 生成，value、label 映射，支持标签、文字、徽标三种表格展示类型，多种显示状态，还有方便的系统配置，对系统配置后台一键管理。

### 🎨 React 技术栈

我们使用了 阿里 Umi Js 以及 AntdPro 组件库，不仅简单易用，并且可以是你的技术更上一层楼，带你体验技术的革新，站在巨人肩膀上享受开发的便捷和乐趣。

### 🌺 Taro 多端小程序

XinAdmin 包含了 Taro 多端小程序演示项目，提供 H5 解决方案，可以基于 XinTaro 开发 微信、支付宝小程序，甚至使安卓、鸿蒙 App 应用。

### 🎉 系统架构

基于 PHP8 + React + TypeScript + UmiJs + Ant Design 等技术栈开发的后台管理系统，不仅可以使你的技术更上一层楼，还可以体验科技带来的乐趣

## 项目截图预览

#### CRUD 表格开发

<ImagePreview float>
  <img width="500px" src="https://file.xinadmin.cn/file/crud.png" alt=""/>
</ImagePreview>
通过对表格组件的操作、字段以及文件生成配置，一键开发基于查询、新增、编辑、删除等表单表格操作，并且可以进行高度的自定义配置，在线开发 CRUD 代码一键生成代码 和 预览效果，mock 模拟表格数据，更便于使用者者进行开发

- 基于 XinTable 增删该查一个对象即可完全配置
- 支持表格功能设置，新增、编辑、删除、查询等操作的开关
- 支持分页配置，操作栏配置，以及查询配置
- 支持字段完整配置，支持单选、多选、输入框等多种字段类型
- 支持表格预览、mock 数据模拟

<br>

#### 权限菜单配置

<ImagePreview float>
  <img src="https://file.xinadmin.cn/file/rule.png" alt=""/>
</ImagePreview>
XinAdmin 主 View 项目采用UmiJs 的动态路由配置，文件系统即路由，并且通过UmiJs 插件前后端文件分组，在后端进行添加菜单路由以及权限配置，可以实现页面、模块、按钮级权限控制
并且拥有管理端（后台）和用户端（前台）两套权限控制。

- 基于 UmiJs 的动态路由，不必手动定义路由，免去路由配置的烦恼
- 文件路径即路由地址，支持路由菜单隐藏，权限开启关闭
- 支持多语言配置、支持无限级子节点

<br>

<ImagePreview float>
  <img src="https://file.xinadmin.cn/file/index.png"/>
</ImagePreview>
多模板门户页面，可直接当作公司官网或者项目首页，还有更多插件模板

<br>

<ImagePreview float>
  <img src="https://file.xinadmin.cn/file/dict.png"/>
</ImagePreview>
字典配置，支持多中种状态

<br>

### 你的 Star 是我熬夜敲键盘更新文档和代码的动力

## 理念

技术无止境，在我享受他人技术成果的时候，也想要为技术做出一份贡献。对于设计理念，我们始终站在巨人的肩膀之上，探索属于我们的全新篇章！

## 项目愿景

我渴望技术，在这个技术大爆发的时代，通过成熟切优秀的项目，构建出一套稳定、可行性强、方便实用的全栈开发框架，提供多行业跨平台解决方案，包括且不限于 CMS、SaaS、CRM、
BPM 等，适用于商城、游戏、即时通信、业务管理、博客等领域。不断探索新环境，结合人工智能，实现 0 代码的同时支持高度自定义，可视化编程，让数字化、信息化方案不再腐败。

## 未来可期

我们正在努力维护这个项目，相信不久的将来 Vue 版本也会出现在我们视野中。不仅如此，Think PHP 也不是后台的唯一选择，相信 Spring Boot 和 Laravel 等同样优秀

## 即将上线

1. 门户设计器，AntdV 图表
2. 数据导入导，报表设计
3. 文章管理 CMS 系统
4. Taro 多端应用
5. APP 手机端页面设计器
