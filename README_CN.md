# Packet Capture Pro

[English Version](README.md)

⚠️ **注意：Packet Capture Pro 是非开源项目，本仓库仅用来管理需求和用户反馈。**

[Packet Capture Pro](https://pcp.realsignal.com/zh-CN) 是新一代高级跨平台数据抓包工具。Packet Capture Pro 具有全平台、无需 Root、轻量级、高性能、实时同步等优点，理念是让网络调试更快更简单，助力开发者和技术人员提高生产力！现已支持 Android、iOS、Windows 和 macOS 四大平台。

官方网站：https://pcp.realsignal.com/zh-CN

## Packet Capture Pro 是什么？

**Packet Capture Pro = 专业抓包工具 + 全链路透视 + 跨平台协同**

Packet Capture Pro 是专为开发者和技术人员设计的网络调试与开发工具，基于先进的虚拟机技术实现安全抓包。相比传统抓包工具，Packet Capture Pro 无需 Root/越狱权限，支持移动端到 PC 端的实时数据镜像，一个工具实现多平台协同调试。

### 核心优势

#### 🔒 安全便捷
- **无需 Root 权限**：Android 端基于虚拟机的安全抓包技术
- **iOS 无需越狱**：设备无需越狱即可使用
- **HTTPS 解密**：支持 HTTPS 流量解密分析
- **隐私保护**：所有数据仅存储在您的设备上，不会上传至任何服务器

#### 🌐 全平台支持
- **Android**：支持最新 Android 系统
- **iOS**：兼容 iPhone 和 iPad
- **Windows & macOS**：桌面端协同调试
- **跨平台同步**：每个账号在不同平台可同时在线 1 个设备

#### ⚡ 强大功能
- **实时数据镜像**：移动端数据实时投射到 PC 大屏
- **多设备协同**：支持多设备同时投射
- **智能重写重放**：灵活的数据包重写与精准重放
- **全链路透视**：可视化联调、安全检测、第三方协议分析

## 功能特性

### 1. 流量分析

#### Android 端
- [x] 支持 HTTP/HTTPS/WebSocket 抓包
- [x] 支持多种格式抓包数据解析展示
- [x] 支持 TLSv1.1、TLSv1.2 加密协议
- [x] 请求响应对比
- [x] 请求重写与重放功能
- [x] 实时投射到 PC 客户端
- [x] 基于虚拟机的安全抓包
- [x] 黑白主题随心切换
- [x] 多类型快速检索
- [x] 数据导入 & 导出
- [x] 工具箱（加解密、证书 Hash、正则表达式）

#### iOS 端
- [x] 支持 HTTP/HTTPS/WebSocket 抓包
- [x] 支持多种格式抓包数据解析展示
- [x] 支持 TLSv1.1、TLSv1.2、TLSv1.3 加密协议
- [x] 请求响应对比
- [x] 请求重写与重放功能
- [x] 设备无需越狱
- [x] 实时投射到 PC 客户端
- [x] 黑白主题随心切换
- [x] 多类型快速检索
- [x] 数据导入 & 导出
- [x] 工具箱（加解密、正则表达式）

#### Windows & macOS 端
- [x] 支持 HTTP/HTTPS 抓包
- [x] 支持多种格式抓包数据解析展示
- [x] 请求响应对比
- [x] 请求重放功能
- [x] 手机到电脑的数据镜像
- [x] 多类型快速检索
- [x] 数据导入 & 导出

### 2. 调试功能

#### 全链路透视
✅ **可视化联调 · 安全检测 · 第三方协议**
- 实时查看 API 请求/响应内容，定位接口超时、数据错误等故障
- 验证前端发送的数据格式是否正确，检查后端返回数据完整性
- 分析明文传输敏感信息（如密码、Token），发现未加密通信风险
- 支持多种格式抓包数据解析展示
- 多类型快速检索

#### 数据包重写与重放
✅ **全面调试工具**
- 快速构建服务器错误（500）等复杂测试场景
- 基于真实流量复现用户端偶发问题，消除"开发环境无法复现"的盲区

#### 跨平台数据镜像
✅ **专注实现移动端数据在 PC 端的可视化**
- 突破手机小屏限制，在 PC 大屏上实时查看、搜索、过滤 App 网络请求
- 支持多设备同时投射
- 助力开发者/运维人员高效完成网络调试与数据分析

### 3. 用户体验

- [x] **黑白主题切换**：极简与深邃，风格一秒切换
- [x] **多格式支持**：JSON、XML、HTML、图片等多种格式智能解析
- [x] **快速检索**：支持 URL、方法、状态码、内容等多维度搜索
- [x] **数据持久化**：支持抓包数据导入导出，方便数据共享和回溯

## 下载和安装

Packet Capture Pro 官网提供了最新版本的下载：[点我查看](https://pcp.realsignal.com/zh-CN)

### Android 安装

<a href="https://play.google.com/store/apps/details?id=com.realsignal.packetcapturepro"><img src="public/badges/play.svg" height="45"></a>

您可以从 Google Play 免费获取应用。

### iOS 安装

<a href="https://apps.apple.com/us/app/packet-capture-pro-https/id6742767975"><img src="public/badges/ios.svg" height="45"></a>

您可以从 App Store 免费获取应用。

### Windows 安装

从官网下载：[点我查看](https://pcp.realsignal.com/zh-CN)

在 Windows 上，您下载的是 `Setup.exe`，按照 Setup 安装程序指引即可。

### macOS 安装

从官网下载：[点我查看](https://pcp.realsignal.com/zh-CN)

在 macOS 设备上，打开 DMG 文件后拖拽进`应用程序`文件夹即可。

## 移动端支持

Packet Capture Pro 移动端支持单独使用，也支持与桌面端协同使用。

- **独立使用**：可以单独进行流量分析和网络调试，无需依赖桌面端
- **协同模式**：移动端可以实时将流量数据投射到桌面端，在 PC 大屏上进行更高效的分析和调试

您可以从 Play Store 和 App Store 免费获取应用。

<a href="https://play.google.com/store/apps/details?id=com.realsignal.packetcapturepro"><img src="public/badges/play.svg" height="45"></a>&nbsp;&nbsp;
<a href="https://apps.apple.com/us/app/packet-capture-pro-https/id6742767975"><img src="public/badges/ios.svg" height="45"></a>

## 使用场景

### 开发调试
- API 接口联调与测试
- 定位网络请求超时问题
- 验证数据格式与完整性
- 复现生产环境网络问题

### 安全检测
- 检测明文传输敏感信息
- 分析应用网络安全风险
- 验证加密通信实现
- 第三方 SDK 流量分析

### 性能优化
- 分析网络请求耗时
- 优化接口调用策略
- 检测重复请求
- 减少不必要的网络开销

## 隐私与安全政策

- Packet Capture Pro 专为开发者和技术人员设计，旨在支持网络调试与开发工作
- 为确保合法合规使用，严禁将本工具用于任何非法目的，任何因非法使用所产生的后果，均由使用者自行承担，与本公司无关
- **我们不收集、存储或共享任何用户抓包数据。所有的数据仅存储在您的设备上，不会上传至任何服务器**

## 使用文档

如需详细的使用说明和教程，请访问我们的官方文档：

**📖 [用户手册](https://pcp.realsignal.com/tutorials/manual)**

用户手册包含：
- 📱 **Android** - Android 设备完整使用指南
- 🍎 **iOS** - iPhone 和 iPad 详细操作说明
- 💻 **Windows** - 桌面端客户端使用指南
- 🖥️ **macOS** - Mac 应用程序教程
- 🔧 **Emulator** - 模拟器配置和设置

## 问题反馈

如果您在使用过程中遇到问题或有功能建议，欢迎通过以下方式反馈：

- [提交 Bug 报告](https://github.com/REALSIGNAL/packetcapturepro-app/issues/new?template=bug_report.yml)
- [提交功能请求](https://github.com/REALSIGNAL/packetcapturepro-app/issues/new?template=feature_request.yml)
- [咨询使用问题](https://github.com/REALSIGNAL/packetcapturepro-app/issues/new?template=question.yml)

## 联系我们

- 官方网站：https://pcp.realsignal.com/zh-CN
- 更多网络工具：[NetSim Pro](https://nsp.realsignal.com/)

---

**Realsignal Pte. Ltd. © 2026 All rights reserved**
