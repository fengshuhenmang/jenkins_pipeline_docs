---
title: 流水线集成篇
weight: 15
pre: "<b>3. </b>"
chapter: true
---

### Chapter 3

# 流水线集成篇

{{% notice tip %}}
😺您好，本模块主要讲解Jenkins如何与其他工具链系统集成， 注意不会讲解太多关于外围系统的知识，如需了解更多可以查阅外围系统的官方文档！
{{% /notice %}}


| 章节名称 | 章节内容 |
| ------ | ----------- |
| [3-1 构建发布工具集成](chapter01/_index.en.md) |本章我们将学习Jenkins与常用的构建发布工具集成|
| [3-2 用户认证系统集成](chapter02/_index.en.md) | 本章我们将为大家讲述用用户认证系统集成|
| [3-3 版本控制系统集成](chapter03/_index.en.md) |本章我们将学习Jenkins与版本控制系统集成|
| [3-4 质量管理平台集成](chapter04/_index.en.md) | 本章主要讲述Jenkins与质量管理平台集成|
| [3-5 制品仓库集成](chapter05/_index.en.md) | 本章我们主要讲述Jenkins与制品库集成 |
| [3-6 需求管理平台集成](chapter06/_index.en.md) | 本章我们主要讲述Jenkins与需求管理平台集成 |
| [3-7 容器PaaS平台集成](chapter07/_index.en.md) | 本章我们主要讲述Jenkins与与容器PaaS平台集成 |
| [3-8 自动化接口测试](chapter08/_index.en.md) | 本章我们主要讲述Jenkins完成自动化接口测试 |


## FAQ

### Q1什么是集成？
所谓的集成是通过Jenkins与外部系统或工具之间的调用，而不是Jenkins本身具备其他外围系统的功能。例如：与maven集成，我们不能去认为Jenkins自身已经具有maven打包构建的功能，而是jenkins调用maven去进行打包构建！ 所以打包出现的问题未必一定是Jenkins的问题，80%因为代码无法完成编译等步骤导致的。