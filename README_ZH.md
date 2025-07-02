 <h1 align="center">Memcached分布式内存缓存系统</h1>
  <p align="center">
    <a href="README.md"><strong>English</strong></a> | <strong>简体中文</strong>
  </p>


## 目录

- [仓库简介](#项目介绍)
- [前置条件](#前置条件)
- [镜像说明](#镜像说明)
- [获取帮助](#获取帮助)
- [如何贡献](#如何贡献)

## 项目介绍

[Memcached](https://github.com/memcached/memcached)  是一款‌分布式内存缓存系统‌，，专为动态 Web 应用加速而设计。其核心功能是通过内存存储高频访问数据（如数据库查询结果），显著降低后端数据库负载，提升应用响应速度‌。本商品基于鲲鹏服务器的Huawei Cloud EulerOS 2.0 64bit系统，提供开箱即用的Memcached。

## 核心特性

- **‌内存存储‌：** 数据存储在内存中，读写速度远超磁盘，适用于高频访问场景；
- **分布式架构‌：** 通过一致性哈希算法水平扩展，支持多节点分布式存储；
- **‌无持久化‌：** 服务器重启或崩溃后数据丢失，需应用程序额外同步更新；
- **‌高并发处理‌：** 采用多线程或事件驱动模型，单台服务器可处理每秒数万次请求。

本项目提供的开源镜像商品 [**Memcached分布式内存缓存系统**](https://marketplace.huaweicloud.com/contents/cc343a9d-caf5-4b8e-acf5-b644f6ddffe9#productid=OFFI1121975571984920576) 已预先安装1.6.38版本的Memcached及其相关运行环境，并提供部署模板。快来参照使用指南，轻松开启“开箱即用”的高效体验吧。


> **系统要求如下：**
> - CPU: 2vCPUs 或更高
> - RAM: 4GB 或更大
> - Disk: 至少 40GB

## 前置条件
[注册华为账号并开通华为云](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## 镜像说明

| 镜像规格                                                                                                      | 特性说明 | 备注 |
|-----------------------------------------------------------------------------------------------------------| --- | --- |
| [Memcached-1.6.38-kunpeng](https://github.com/HuaweiCloudDeveloper/memcached-image/tree/Memcached-1.6.38-kunpeng) | 基于鲲鹏服务器 + Huawei Cloud EulerOS 2.0 64bit 安装部署 |  |

## 获取帮助
- 更多问题可通过 [issue](https://github.com/HuaweiCloudDeveloper/memcached-image/issues) 或 华为云云商店指定商品的服务支持 与我们取得联系
- 其他开源镜像可看 [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos)

## 如何贡献
- Fork 此存储库并提交合并请求
- 基于您的开源镜像信息同步更新 README.md