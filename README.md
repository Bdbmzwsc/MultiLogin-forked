[English](https://github.com/CaaMoe/MultiLogin/blob/v6/README.en.md)
<div align="center">

# MultiLogin

_✨ 正版与多种外置登录共存 ✨_

</div>

> [!CAUTION]  
> 这是一个非官方fork，尝试更新MultiLogin并使其在最新版Velocity上工作  
> 只针对Voidix Network使用的Velocity版本进行适配，但尽力保持通用性    
> 使用风险自负！

## 概述

MultiLogin 是一款主要为 Minecraft 代理端设计的插件，旨在实现对正版与多种外置登录共存的支持，用于连接两个或多个外置验证服务器下的玩家，使他们能够在同一个服务器上一起游戏。

## 特性

* 支持多达 128 个不同来源的 Yggdrasil 同时共存
* 鉴权代理、重试机制
* 游戏内档案管理系统
* 异步/同步皮肤修复机制
* 支持接管 Floodgate

## 安装

最低需要 `Java 25`， 不需要安装 `authlib-injector` ，没有任何前置插件，也不需要添加和更改 `JVM` 参数

~~把大象装进冰箱需要几步？~~

1. 构建插件
2. 丢进 plugins
3. 启动服务器

## 配置

详见 [Wiki](https://github.com/CaaMoe/MultiLogin/wiki)

## 构建

1. 克隆这个项目
2. 执行 `./gradlew shadowJar` / `gradlew shadowJar`
3. 在 `*/build/libs` 下寻找你需要的

## 原项目贡献者

<a href="https://github.com/CaaMoe/MultiLogin/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=CaaMoe/MultiLogin"  alt="作者头像"/>
</a>
