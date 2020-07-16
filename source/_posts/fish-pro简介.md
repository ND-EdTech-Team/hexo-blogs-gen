---
title: fish-pro简介
date: 2020-07-16 19:56:11
tags:
---
# fish pro 是什么

fish pro 是一套基于 react 的 **通用后台管理最佳实践**，为工程院提供一套管理后台快速开发能力，可以通过：[http://fish-design-pro-test.k8s.sdp.nd/](http://fish-design-pro-test.k8s.sdp.nd/#/demo/crud/modal) 进行预览。

<a name="uJe4M"></a>
## 能力
<a name="ArtqG"></a>
### 1、快速创建后台项目的能力
通过 [toolkit](http://githoniel.gitee.io/toolkit-doc/#/) 命令行（[@gem-mine/cli](http://githoniel.gitee.io/toolkit-doc/#/zh-cn/api/gmc/readme)）直接创建，未来还可以通过可视化界面进行。依托于 [toolkit](http://githoniel.gitee.io/toolkit-doc/#/) 还能够进行项目的版本检测与自动化升级，也就是说 fish pro 在不断发展的同时，你会及时收到其什么时候发布了版本，更新的内容，并且可以自动化升级。

<a name="A9PBZ"></a>
### 2、成熟、高效的项目构建能力
基于 [toolkit](http://githoniel.gitee.io/toolkit-doc/#/) 的构建能力（[@gem-mine/script](http://githoniel.gitee.io/toolkit-doc/#/zh-cn/api/gms/readme)），当然还支持进行自定义处理。例如你可以添加 plugin、loader 以及任何你想自定义 webpack 的能力。

<a name="aF8uG"></a>
### 3、健壮的 react 基础能力
集成了 react 中非常常用的两个能力

- 数据流管理（[@gem-mine/durex](https://www.yuque.com/gem-mine/util/durex-overview)），基于redux 但比 redux 好用太多
- 路由管理（[@gem-mine/durex-router](https://www.yuque.com/gem-mine/util/router-overview)），配置型路由管理，包括了权限配置、路由拆包按需等能力

<a name="aTztv"></a>
### 4、方便、实用的工具库、UI 库

- 请求库（[@gem-mine/request](https://www.yuque.com/gem-mine/util/request-overview)），支持多域、多环境请求能力，通过切面定制通用异常、loading 处理。同时 fish pro 在此基础上适配 WAF 跨域能力
- 不可变数据（[@gem-mine/immutable](https://www.yuque.com/gem-mine/util/immutable-overview)），小而可爱的 immutable 工具，提升性能的同时也提升了编码体验
- 国际化能力（[@gem-mine/intl](https://www.yuque.com/gem-mine/util/intl-overview)），简单有效的多语言能力，支持本地、远程模式
- 工程院 SDK 集合（[@sdp.nd/one](https://www.yuque.com/gem-mine/util/one-overview)），包装好了 one，可以快速接入工程院的 uc、oms、rbac 等能力
- fish UI ，这个无需多言，历时两年多，工程院 react 技术栈 PC WEB 项目标配 UI 组件库

<a name="i0lN9"></a>
### 5、提供后台通用能力

- 提供后台常用的布局、菜单、导航、面包屑能力，菜单、面包屑通过配置化方式编写。同时这些能力可以通过 url 参数进行关闭或打开，可以方便于作为独立页面接入其他站点（例如聚合后台）
- 精心准备了常用的开发模式：各种表单表格（单页、多页、行内、卡片）、富文本、图表 等等
- 提供了通用的组件，包括：通用请求loading、异常处理、403、404、500 处理 等等

<a name="Vhqtw"></a>
### 6、满足个性化需求

- 构建能力自定义能力，你可以自定义 webpack 相关能力，例如 plugins、loaders 等等
- 页面、组件的自定义能力，对于页面、组件只需要满足 react 技术栈即可进行开发

<a name="bZ09D"></a>
### 7、符合工程院 UE 设计规范
和 UEDC 团队配合，遵循 UE 对应规范

<a name="SBprF"></a>
## 选型判断
如果你需要开发一个后台管理系统，存在以下的需求：

- 希望具有通用的后台能力，例如：布局、菜单、面包屑 等能力
- 希望后台能够快速接入工程院基础能力：UC、RBAC、CS 等
- 希望后台可以被聚合后台 或其他前台项目快速接入复用
- 希望后台具有较强的自定义能力，例如：主体内容个性化展示

<a name="VdfhR"></a>
## 相关截图
后台：<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/85699/1561702419785-e1a2b3a5-756e-4ac5-9399-98361ef35997.png#align=left&display=inline&height=834&name=image.png&originHeight=1668&originWidth=2872&size=394994&status=done&style=none&width=1436)

接入聚合后台：<br />![image.png](https://cdn.nlark.com/yuque/0/2019/png/85699/1561702630343-0f83a10e-3fe5-446b-8827-6c9fdb4b375f.png#align=left&display=inline&height=795&name=image.png&originHeight=1590&originWidth=2876&size=378880&status=done&style=none&width=1438)
<a name="EEKwz"></a>
## 
