# 简介

## 项目构成
VideoOS open提供云服务版本和开源版本。云服务版本提供更加丰富的功能，免去了本地化部署的繁琐步骤，适合大部分中小型客户；开源版本只提供了基础的小程序管理和投放功能，可以进行二次开发集成，适合大型客户。

!!! note
    如果是使用Video++提供的[云服务](https://os-saas.videojj.com)，只需要接入移动端SDK；如果需要本地化部署，另外需要单独部署服务端和控制台。

### 移动端SDK
移动端SDK提供用户在自己的移动端APP视频播放器上接入小程序的能力，要求开发者具有一定的移动端开发能力

SDK对接文档请参考：  

* [VideoOS iOS SDK](iOS-SDK.md)
* [VideoOS Android SDK](Android-SDK.md)

试用接入SDK的[DEMO](demo.md)

### 控制台
移动端SDK接入完成后，请登入[控制台](https://os-saas.videojj.com)。控制台提供创建小程序，管理投放等日常运营功能，查看[控制台操作手册](manual.md)

### lua小程序
视频小程序基于[LuaViewSDK](https://github.com/alibaba/LuaViewSDK)，一个小程序由若干lua脚本文件加一个json配置文件组成

## 开源
开源版本的项目代码已经在github公开：[https://github.com/VideoOS](https://github.com/VideoOS)，大家可以自行下载源码进行本地化部署

## 关于PC Web端
新版本的VideoOS open聚焦移动端开发，暂不支持PC Web端，如果你的产品形态是PC Web，那么请移步[VideoOS 老版本](oldversion.md)

## 快速启动
本地化部署流程相对比较复杂，适用于有一定开发和运维能力的技术团队。为了便于测试，我们提供了 Docker Compose 的快速启动方式，你可以按照以下流程快速搭建一个测试环境，具体请参考：[get started](get-started.md)
