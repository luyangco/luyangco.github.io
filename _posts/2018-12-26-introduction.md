---
layout: post
title: "VoltDB中文手册提纲"
subtitle: 'VoltDB Chinese manual outline"'
author: "Ylu"
header-style: text
lang: en
tags:
  - VoltDB
  - Documentation
  - 中文
  - 🇬🇧
---

### 手册提纲:
* 搭建一个3节点voltdb集群分解，
  * 下载链接
  * 配置文件
  * k=0, //说明什么意思
  * siteperhost=x //说明什么意思
    等等..
  * 目录结构
  * 初始化
  * 启动
  * 常用监控命令
* java写一个分区存储过程
  * 为什么分区
  * 建分区表和复制表/ttl
  * CRUD操作/join/subquery
  * 返回多个结果集
  * 编译（怎么在ideaj 和 eclipse里面）
* java client
  * client api 说明
  * 链接到每个节点
  * 开启多个连接线程
  * 同步调用
  * 异步调用
  * adhoc
  * volttable 组装和解析

### 运维手册提纲：
* 启动、停止
* 执行计划
* 监控（单集群状态、资源利用率、性能、慢查、内存使用告警等）
* 扩容
* DR/XDCR状态监控
* 用户权限（之前有了可以合并在一起）
