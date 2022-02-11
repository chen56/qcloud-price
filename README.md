# 腾讯云报价工具

本报价工具所有数据均来自于[腾讯云官网](https://cloud.tencent.com).

## 下载说明

| 版本 | 下载连接                                                                                 | 备注     |
| ---- | ---------------------------------------------------------------------------------------- | -------- |
| 0.3  | [price.xlsx](https://ruf.coding.net/p/qcloud/d/qcloud-price/git/raw/release-0.3/price.xlsx) | 1. 删除原各产品自己的特殊字段，合并所有产品配置到以下字段：规格、CPU、内存、硬盘、带宽、节点 <br/>2. 增加EMR报价器 |
| 0.2  | [price.xlsx](https://ruf.coding.net/p/qcloud/d/qcloud-price/git/raw/release-0.2/price.xlsx) | 增加产品过滤器 |
| 0.1  | [price.xlsx](https://ruf.coding.net/p/qcloud/d/qcloud-price/git/raw/release-0.1/price.xlsx) | 首发版本 |

## 当前支持的报价产品

| 产品名            | 产品标识 |   备注       |
| ----------------- | -------- | ------------ |
| 云服务器          | CVM      |              |
| 云数据库 MySQL    | CDB      |             |
| 云数据库 Redis    | CRS      |             |
| NAT 网关          | NAT      |             |
| 共享带宽包        | BWP      |             |
| VPN 连接          | VPN      |            |
| 负载均衡          | CLB      |             |
| 弹性 MapReduce    | EMR      |             |
