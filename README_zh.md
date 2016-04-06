# frp

[![Build Status](https://travis-ci.org/fatedier/frp.svg)](https://travis-ci.org/fatedier/frp)

[README](README.md) | [中文文档](README_zh.md)

>frp 是一个高性能的反向代理应用，可以帮助你轻松的进行内网穿透，对外网提供服务。

## 开发状态

frp 目前正在前期开发阶段，master分支用于发布稳定版本，dev分支用于开发，您可以尝试下载最新的 release 版本进行测试。

**在 1.x 版本以前，交互协议都可能会被改变，不能保证向后兼容。**

## 快速开始

[QuickStart](doc/quick_start_en.md) | [使用文档](doc/quick_start_zh.md)

## 架构

![architecture](doc/pic/architecture.png)

## frp 的作用?

* 利用处于内网或防火墙后的机器，对外网环境提供http服务。（针对http的优化正在开发中）
* 利用处于内网或防火墙后的机器，对外网环境提供tcp服务。
* 可查看通过代理的所有http请求和响应信息。（待开发）

## 贡献代码

如果您对这个项目感兴趣，并且想要参与其中，我们非常欢迎！

* 如果您需要提交问题，可以通过 [issues](https://github.com/fatedier/frp/issues) 来完成。
* 如果您有新的功能需求，可以反馈至 fatedier@gmail.com 共同讨论。

## 贡献者

* [fatedier](https://github.com/fatedier)
* [Hurricanezwf](https://github.com/Hurricanezwf)
* [vashstorm](https://github.com/vashstorm)