---
title: 快速上手
order: 1
---

# 快速上手

&nbsp;&nbsp;&nbsp;&nbsp;本项目的技术栈选用 laravel 和 ant design， 在开始之前，我想你应该已经熟练了解了 Html、Css、JavaScript 以及 PHP 的相关知识，在此前提之下，推荐你去了解以下相关文档及内容:
JS 框架: <a href="https://react.docschina.org/" target="_blank" rel="noreferrer">React</a>、
JS 框架: <a href="https://umijs.org/" target="_blank" rel="noreferrer">Umi Js</a>、
React 组件库: <a href="https://ant.design/index-cn/" target="_blank" rel="noreferrer">Ant Design</a>、
PHP 框架: <a href="https://laravel.com/" target="_blank" rel="noreferrer">Laravel</a>，当然我们也会在文档中尽可能的去详细的描述任何一个相关的知识点，以便新手也可以快速上手本项目

:::warning
如果你还没有基础的开发环境，建议你先阅读[环境准备](/laravel/dev)章节
如果你想使用本项目，强烈建议你花几分钟时间阅读一下本文章！如果在安装过程中有任何错误，也请你加入我们的[官方 qq 群](/introduce/author#联系我)来获取帮助。
:::

## 获取项目

方法 1：克隆项目到本地目录，你可能需要安装 <a href="https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git" target="_blank" rel="noreferrer">Git</a>，
我们推荐你使用 git 对项目进行版本管理，也建议你 fork XinAdmin 项目以便更新最新版 XinAdmin

```shell
# 新建项目文件夹

git clone https://github.com/xinfarme/Xin-Laravel.git

```

方法 2：直接下载项目压缩包，到本地解压

```shell
# 下载地址
https://github.com/xinfarme/Xin-Laravel
```

## 项目目录

下载或者解压之后你会看到这样一个文件目录

```bash

```

## 后端项目启动

### 1、安装 PHP 依赖

```shell
# 执行依赖安装命令
composer install

# 如果安装速度较慢可以先切换阿里镜像源，安装失败或提示版本不存在请多换几个镜像重试！！！
composer config -g repo.packagist composer https://mirrors.aliyun.com/composer/  # 切换阿里云镜像
# 镜像地址
# composer        https://packagist.org  官方镜像
# phpcomposer     https://packagist.phpcomposer.com 中文镜像
# aliyun          https://mirrors.aliyun.com/composer 阿里云镜像
# tencent         https://mirrors.cloud.tencent.com/composer 腾讯云镜像
# huawei          https://mirrors.huaweicloud.com/repository/php 华为云镜像
# 其它镜像
# laravel-china   https://packagist.laravel-china.org
# cnpkg           https://php.cnpkg.org cnpkg
# sjtug           https://packagist.mirrors.sjtug.sjtu.edu.cn
```

### 2、 配置环境变量

复制后端项目文件夹中的 .example.env 文件 并 重命名为 .env

在 .env 文件中写入数据库账户密码以及数据库名

```text

```

### 3、导入数据库文件

导入数据库文件

```shell
# 运行后端项目

```

### 4、运行后端项目

```shell
# 运行后端项目

```

测试访问 `loaclhost:8000` 出现 json 即可

## 安装前端依赖

```shell
# 切换到 前端 项目目录
cd ./web

# 使用pnpm 安装依赖 ，如果你没有安装 pnpm 请参阅环境准备一章安装环境变量
pnpm install

# 如果安装速度较慢可以切换npm和pnpm镜像
# 切换 npm 镜像
npm config set registry https://registry.npmmirror.com
# 切换 pnpm 镜像
pnpm config set registry https://registry.npmmirror.com
```

安装成功之后，你可以启动项目执行以下命令来启动项目

```shell
# 运行前端项目
pnpm run dev

```

自此，你可以通过 http://127.0.0.1:3000 来访问你的项目