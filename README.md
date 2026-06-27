# 🚀 FlexProtocol Serial Port

[![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Android-blue?style=flat-square)](#)
[![Release](https://img.shields.io/github/v/release/Jerrychenjikai/FlexProtocol-Serial-Port?style=flat-square&color=orange)](#)
[![License](https://img.shields.io/badge/License-Commercial-red?style=flat-square)](#)

这是一个专业的**跨平台（Windows 桌面端 & Android 移动端）串口+蓝牙数据采集、动态协议解析与实时可视化分析工具**。本仓库作为官方唯一的公开发行版分发渠道，不包含任何源代码，仅提供经过安全签名、即开即用的编译成品。

---

## ✨ 核心特性 / Core Features

* **⚡ 跨平台同构体验**：同时支持 Windows 桌面端与 Android 手机/平板（通过 OTG 挂载），两端具备完全一致的操控体验与底层硬件通信效率。
* **🧩 动态协议组装引擎**：
    * **TX 控制下发**：支持自由拼接固定 Hex 字节与动态变量（如采样率 `SPS`、持续时长 `Duration`），支持大/小端字节序切换。
    * **RX 粘包滑窗解析**：内置高性能滑动窗口对齐算法，支持固定帧长或变长帧（帧头/帧尾对齐），支持 Sum8、Xor8、CRC16 等多种数据校验。
* **📊 高性能实时示波器**：轻松支撑多通道、几十万级高频数据点的实时流畅波形绘制。
* **💾 数据持久化与导出**：自定义的控制与解读协议可一键序列化保存在本地；采集完毕的数据支持一键导出为标准的 `.csv` 文件。

---

## 📥 下载安装 / Download

请直接前往本仓库的[release页面](https://github.com/Jerrychenjikai/FlexProtocol-Serial-Port/releases)下载最新版本的安装包：

| 平台 (Platform) | 文件名 (File Name) | 说明 (Description) |
| :--- | :--- | :--- |
| **💻 Windows** | `FlexProtocol Serial Port.zip` | 解压即用，绿色免安装。 |
| **🤖 Android** | `FlexProtocol Serial Port.apk` | 手机/平板直接安装（需开启“允许未知来源安装”）。 |

---

## 💎 升级 Pro 专业版 / Upgrade to Pro

本软件的基础功能完全免费。如果您需要解锁高级特性（例如**添加更多通道变量映射、解除高级协议编辑限制**），可以通过以下自动化发卡渠道购买离线永久激活码（License Key）：

### 🛒 购买渠道 (Purchase Links)

* **🌍 海外用户 (International Users)**:
    * [Buy on Lemon Squeezy](你的LemonSqueezy商品链接) (支持 Credit Card / PayPal / Apple Pay)
* **🇨🇳 国内用户 (Mainland China Users)**:
    * [通过 面包多 购买](https://mbd.pub/o/bread/YZaTmpxuag==) (支持 微信支付 / 支付宝)

> **💡 激活说明**：购买成功后，您将获得一个激活码。打开应用，在协议编辑页面触发弹出窗口后粘贴激活码并点击验证，重启软件即可永久解锁全部高级功能（支持完全离线无网环境验证）。

---

## 🔒 安全性与免责声明 / Security & Disclaimer

1. **纯净无毒**：本仓库发布的二进制成品均由本地原生干净环境编译打包，不包含任何恶意代码或联网逻辑。
2. **硬件兼容性**：Android 端需确保您的设备支持 USB 主机模式（OTG），且使用了高品质的电平转换芯片（如 CH340, PL2303, FTDI 等）。
3. **商业许可**：本软件属于闭源商业数字资产，严禁对编译后的二进制文件进行逆向工程、二次打包或未经授权的非法传播。
