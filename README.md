# WirelessKeyView 简体中文语言文件 🇨🇳

[![Platform](https://img.shields.io/badge/platform-Windows-blue.svg)](https://www.nirsoft.net/utils/wireless_key_view.html)
[![Language](https://img.shields.io/badge/language-%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87-brightgreen.svg)](https://github.com/DaXiGua732/wirelesskeyview-chinese)
[![License](https://img.shields.io/badge/license-MIT-yellow.svg)](LICENSE)

为 [NirSoft](https://www.nirsoft.net/) 出品的 **WirelessKeyView** 制作的简体中文语言文件（非官方汉化）。

- **适用软件**：WirelessKeyView（Nir Sofer 出品）
- **适用版本**：2.23
- **文件**：`WirelessKeyView_lng.ini`
- **编码**：ANSI（GBK，CRLF），中文 Windows 直接可用
- **翻译者**：[DaXiGua732](https://github.com/DaXiGua732)

---

## 软件简介

**WirelessKeyView** 是 **Nir Sofer**（NirSoft 作者）出品的一款无线网络密钥恢复工具。它会从系统存储中恢复 Windows 保存过的无线网络（Wi-Fi）密钥：

- **网络名称（SSID）**、密钥类型（WEP / WPA-PSK / WPA2-PSK / WPA3-SAE）
- 密钥的十六进制与 ASCII 格式、认证方式、加密方式、连接类型
- 适配器名称与 GUID、最后修改时间、配置文件来源

支持导出所选/全部密钥、导入导出文件（便于备份迁移）、复制二维码（手机扫码直连）等，并可从外部 Windows 安装或远程系统提取密钥。忘掉 Wi-Fi 密码时最常用的小工具。

官网：<https://www.nirsoft.net/utils/wireless_key_view.html>

## 使用方法

1. 从 [Releases](https://github.com/DaXiGua732/wirelesskeyview-chinese/releases) 或直接下载 `WirelessKeyView_lng.ini`；
2. 将文件放到 `WirelessKeyView.exe` 所在目录；
3. 重新启动 WirelessKeyView，界面即变为简体中文，**关于**窗口中会显示翻译者信息。

> 💡 想恢复英文界面？直接删除或改名该 ini 文件即可。

### 语言文件机制说明

WirelessKeyView 支持 NirSoft 标准语言包机制：运行 `WirelessKeyView.exe /savelangfile` 会生成英文模板 `WirelessKeyView_lng.ini`，将模板中的字符串翻译为目标语言并保持同名同目录，程序启动时自动加载。

## 汉化范围

- ✅ 主菜单、右键菜单（含快捷键）
- ✅ 属性、高级选项、列设置等对话框
- ✅ 全部状态文本与提示
- ✅ 密钥类型与列标题（SSID / 密钥 / 认证 / 加密等）

## 许可与版权说明

### 原软件（WirelessKeyView）

- 作者与版权：**Nir Sofer**（[NirSoft](https://www.nirsoft.net/)），**免费软件（Freeware），非开源**。
- 依据 [NirSoft 免费软件许可协议](https://www.nirsoft.net/nirsoft_license.html)：
  - 允许免费使用与分发（含网络分发）；
  - **禁止**收费、出售或作为商业产品的一部分分发；
  - 分发官方程序包时必须包含全部文件且不得修改。
- 本仓库**不包含**原软件可执行文件，仅分发语言文件。

### 本汉化文件（WirelessKeyView_lng.ini）

第三方翻译作品，按 [MIT License](LICENSE) 授权。与 NirSoft 官方团队无任何关联，使用本补丁即表示你同时接受原软件的许可条款。

### 免责声明

本汉化文件按 "AS IS" 提供，不附带任何明示或隐含的担保。请仅配合正版、官方渠道获取的 WirelessKeyView 使用。

*WirelessKeyView 与 NirSoft 名称归各自权利人所有；本仓库仅提供翻译文件。*
