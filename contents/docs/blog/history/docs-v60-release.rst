---
created: 2016-06-01 17:03:00
creator: Kendom
description: ''
title: 易度文档管理系统 V6.0 版本发布
---


====================================
易度文档管理系统 V6.0 版本发布
====================================


v6.0 版本是一个大的版本改进，从底层架构，到上层UI，以及扩展开发接口，都做了比较大的改变 。主要的改进包括：

文档方面的改进功能点
============================
* 文档支持分支、合并操作
* 文档的状态，之前的发布改为归档，独立新增发布状态。发布和归档的权限策略相同，区别：
   * 发布：审批通过，正在使用
   * 归档：文档不再使用
* 简化文件操作，将一些不常用的规则、关联表单，转移到站点设置中
* 新的文件配额管理API，可以更好的进行文件配额控制
* 任意2个文件都可以进行比较
* 文件也可以排序
* 可控制文件导航树，是否显示某个文件夹
* 更好的文件预览查看器
* 独立的文件打印权限
* 支持审计权限，审计人可以查看操作历史
* 导航树显示支持滚动条

新增客户端：桌面助手
============================
桌面助手是一个新模块。

* 外部编辑改由桌面助手提供。文件保存之后，网页会自动刷新使用新文件。
* 3D文件的预览，改由桌面助手提供
* 桌面助手支持本地文件和线上增加同步，支持冲突解决
* 支持文件批量下载
* 支持文件夹上传

账户管理
==================
* 支持组织结构的转移调整
* 外部公司也可设置组织结构
* 可开放自行注册

通知消息
================
* 消息在右上提示出现
* 通知窗口可大屏展示

即时通讯
================
* 群聊
* 单聊
* 贴图

表单和流程
===================
* 可以对表单的任意字段进行搜索
* 流程支持 转交、协助、委托等临时扭转
* 流程走完，表单自动存档
* 对流程步骤进行分类，更好的查看流程历史
* 流程可自动进入日程
* 支持自动步骤
* 提供上下级审批关系定义的设计器
* 更好的流程图展示
* 支持流程催办
* 个人待办事项安排功能
* 设置流程提醒方式，默认采用邮件提醒
* 站点平台功能
* 网站皮肤管理，支持定制网站
* 站点人员支持多分组管理，可以直接选择外部人员访问站点
* 每个站点，可限制人员的可见范围

项目管理和协作区
=====================
* 之前的项目管理模块，转移为一个可选的系统扩展应用。
* 新增协作区应用。协作区是一个轻量级协作空间，比项目要简单。他取代了之前的部门、工作组的功能。

应用开发
==================
* 完全开放API
* 开发接口做了较大的简化
* 提供更友好的表单、流程的定制界面
* 扩展属性、规则，统一放入软件包进行定义
* 支持皮肤和资源文件的管理
* 导出软件包格式改为yaml，提供edopkg同步工具
* 前端UI库，简化前端的开发

安装部署
========================
* 改为使用docker架构，使用虚拟机部署
* 支持一键在线升级
* 支持增量升级
* 完善的控制台界面，配置更简单

如需体验，可
`免费下载 <http://www.edodocs.com/download.rst>`_

