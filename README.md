# 无波 —— 多源地震灾情信息平台

*Introduction in English please visit: [README-EN.md](README-EN.md)*

无波，意为不起波澜，以喻平安。

项目的核心任务是：该系统提供全国地震灾情信息管理功能，对不同来源的实时地震数据进行上传、解析、处理和分析、发布、可视化的全生命周期，并对外提供查询接口。

## 目录
 - [功能](#功能)
 - [技术栈](#技术栈)
 - [安装与使用](#安装与使用)
 - [贡献](#贡献)
 - [许可证](#许可证)
 - [联系信息](#联系信息)

## 功能

## 技术栈与项目结构

### 技术栈

- 数据层：MySQL 8.0 + Redis + ElasticSearch + Minio
- 业务层：SpringBoot + SpringCloud + Spring Security + JWT + MyBatis
- 消息队列：RabbitMQ
- 依赖管理：Maven

### 项目结构
```
DisasterManagementPlatform/
│
├── gateway/ 网关模块
│   ├── Application.java 启动类
│   └── application.yml 配置文件
│
├── admin-service/ 权限管理模块
│   ├── controller/
│   ├── service/
│   ├── dao/
│   ├── entity/
│   ├── Application.java
│   └── application.yml
│
├── upload-service/ 信息上传模块
│   ├── controller/
│   ├── service/
│   ├── dao/
│   ├── entity/
│   ├── Application.java
│   └── application.yml
│
├── user-service/ 用户模块
│   ├── controller/
│   ├── service/
│   ├── dao/
│   ├── entity/
│   ├── Application.java
│   └── application.yml
│
└── visualization-service/ 可视化模块
    ├── controller/
    ├── service/
    ├── dao/
    ├── entity/
    ├── Application.java
    └── application.yml

```

## 安装与使用

## 贡献

## 许可证
本项目基于 GPL 许可证开源。

## 联系信息
电子邮箱：HoraceGong@163.com  
腾讯QQ：1070236799