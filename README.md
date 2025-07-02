<h1 align="center">Memcached Distributed Memory Caching System</h1>
<p align="center">
    <strong>English</strong> | <a href="README_ZH.md">简体中文</a>
</p>

## Table of Contents

- [Repository Introduction](#repository-introduction)
- [Prerequisites](#prerequisites)
- [Image Description](#image-description)
- [Get Help](#get-help)
- [How to Contribute](#how-to-contribute)

## Repository Introduction

[Memcached](https://github.com/memcached/memcached) is a distributed memory caching system designed to accelerate dynamic web applications. Its core function is to store frequently accessed data (such as database query results) in memory, significantly reducing the load on the backend database and improving the application's response speed. This product provides an out-of-the-box Memcached based on the Huawei Cloud EulerOS 2.0 64-bit system on Kunpeng servers.

## Core Features

- **In-memory Storage**: Data is stored in memory, offering much faster read and write speeds than disk storage, making it suitable for high-frequency access scenarios.
- **Distributed Architecture**: Horizontally scalable through the consistent hashing algorithm, supporting multi-node distributed storage.
- **Non-persistent**: Data is lost when the server restarts or crashes, requiring the application to perform additional synchronization and updates.
- **High-concurrency Processing**: Utilizes a multi-threaded or event-driven model, allowing a single server to handle tens of thousands of requests per second.

The open-source image product [**Memcached Distributed Memory Caching System**](https://marketplace.huaweicloud.com/intl/hidden/contents/1dac4bf3-17b0-4295-9aad-6d4e823cfe54) provided by this project has the 1.6.38 version of Memcached and its related runtime environment pre-installed, and also provides deployment templates. Refer to the usage guide and start your efficient "out-of-the-box" experience now!

> **System requirements are as follows:**
> - CPU: 2 vCPUs or higher
> - RAM: 4GB or more
> - Disk: At least 40GB

## Prerequisites

[Register a Huawei account and activate Huawei Cloud](https://support.huaweicloud.com/usermanual-account/account_id_001.html)

## Image Description

| Image Specification                                                                                                      | Feature Description | Remarks |
|-----------------------------------------------------------------------------------------------------------| --- | --- |
| [Memcached-1.6.38-kunpeng](https://github.com/HuaweiCloudDeveloper/memcached-image/tree/Memcached-1.6.38-kunpeng) | Installed and deployed based on Kunpeng servers + Huawei Cloud EulerOS 2.0 64-bit |  |

## Get Help

- For more questions, you can contact us via [issues](https://github.com/HuaweiCloudDeveloper/memcached-image/issues) or the service support of the specified product on the Huawei Cloud Marketplace.
- For other open-source images, refer to [open-source-image-repos](https://github.com/HuaweiCloudDeveloper/open-source-image-repos).

## How to Contribute

- Fork this repository and submit a merge request.
- Synchronize and update README.md based on your open-source image information.