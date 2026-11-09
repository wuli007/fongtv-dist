# FongTV 视频源（TVBox / FongMi 分发）

本仓库只放 **配置和爬虫 JAR**，源码、分析文档和创建过程在私有仓库中维护。

## 导入链接

| 线路 | 配置地址 |
| --- | --- |
| **GitHub 代理（推荐）** | `https://ghproxy.net/https://raw.githubusercontent.com/wuli007/fongtv-dist/main/config.json` |
| jsDelivr | `https://testingcf.jsdelivr.net/gh/wuli007/fongtv-dist@main/config.json` |
| GitHub raw（需能访问） | `https://raw.githubusercontent.com/wuli007/fongtv-dist/main/config.json` |

导入：

- **TVBox / 影视仓**：设置 → 配置地址 → 粘贴链接 → 确定；
- **FongMi / 影视 TV**：设置 → 点播 → 输入地址。

爬虫 JAR 由本仓库 `spider/custom_spider.jar` 提供（配置里走 ghproxy 下载），
不需要本地服务器。

## 源

| key | 名称 | 分类 / 筛选 |
| --- | --- | --- |
| `cx` | 创享影视 | 类型 / 地区 / 语言 / 排序 |
| `dyrs` | 电影人生 | 类型 / 地区 / 年份 / 排序 |
| `fk` | 飞快TV | 剧情 / 地区 / 语言 / 年份 / 排序 |
| `girigiri` | Girigiri动漫 | 类型 / 年份 / 季度 / 版本 / 原作 / 语言 / 排序 |

## 说明

- 仅做协议/规则适配，不登录、不破解、不绕过付费或 DRM；
- 站点域名/接口可能变化，可用性以实测为准；
- 影视内容版权归各站点与版权方所有，请只在个人环境学习测试，不要公开传播或商用。
