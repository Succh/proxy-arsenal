# 🛜 网络代理软件大全

> 持续更新的网络代理软件汇总，涵盖主流协议和客户端，附带官网、下载地址和安装教程。

## 📋 代理软件横向对比

| 软件 | 协议类型 | 抗封锁性 | 速度 | 易用性 | 跨平台 | 状态 |
|------|----------|----------|------|--------|--------|------|
| **Shadowsocks** | SS/SSR | ⭐⭐⭐ | ⭐⭐⭐ | ⭐⭐⭐⭐ | 全平台 | 维护中 |
| **V2Ray** | VMess/VLESS | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | 全平台 | 已归档 |
| **Xray** | VLESS/XTLS | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | 全平台 | 活跃更新 |
| **Trojan** | Trojan | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 全平台 | 维护中 |
| **Hysteria2** | QUIC | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | 全平台 | 活跃更新 |
| **sing-box** | 多协议 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐ | 全平台 | 活跃更新 |
| **NaiveProxy** | HTTP/2 | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐ | 全平台 | 活跃更新 |
| **TUIC** | QUIC | ⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐ | 全平台 | 维护中 |
| **WireGuard** | WireGuard | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 全平台 | 活跃更新 |
| **Mihomo** | 多协议 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ | 全平台 | 活跃更新 |

## 🔧 代理协议详解

### 1. Shadowsocks

老牌代理协议，轻量高效，适合日常使用。

- 官网：https://shadowsocks.org
- GitHub：https://github.com/shadowsocks
- 适用场景：日常浏览、轻量使用

### 2. V2Ray / Xray

功能强大的代理平台，Xray是V2Ray的升级版，性能更优。

- Xray GitHub：https://github.com/XTLS/Xray-core
- 适用场景：高安全性需求、复杂网络环境

### 3. Trojan

将代理流量伪装成HTTPS流量，隐蔽性极强。

- GitHub：https://github.com/trojan-gfw/trojan
- 适用场景：对抗深度包检测、高隐蔽需求

### 4. Hysteria2

基于QUIC协议的新一代代理工具，速度极快。

- GitHub：https://github.com/apernet/hysteria
- 适用场景：游戏加速、视频通话、跨境办公

### 5. sing-box

通用代理平台，支持几乎所有主流协议，被称为"瑞士军刀"。

- GitHub：https://github.com/SagerNet/sing-box
- 适用场景：多协议需求、高级路由配置

### 6. NaiveProxy

基于HTTP/2的代理工具，流量伪装成正常浏览器访问。

- GitHub：https://github.com/klzgrad/naiveproxy
- 适用场景：极端网络环境、高隐蔽需求

### 7. TUIC

基于QUIC的轻量级代理协议，低延迟高效传输。

- GitHub：https://github.com/EAimTY/tuic
- 适用场景：实时应用、游戏、视频通话

### 8. WireGuard

新一代VPN协议，代码精简，性能优秀。

- 官网：https://www.wireguard.com
- 适用场景：全设备VPN、企业组网

### 9. Mihomo (原 Clash Meta)

Clash的增强分支，支持更多协议和功能。

- GitHub：https://github.com/MetaCubeX/mihomo
- 适用场景：需要Clash配置格式的高级用户

## 🖥️ GUI 客户端大全

### Clash 衍生客户端（基于 Mihomo 内核）

| 客户端 | 平台 | 状态 | GitHub |
|--------|------|------|--------|
| **Clash Verge Rev** | Win/macOS/Linux | ✅ 活跃更新 | https://github.com/clash-verge-rev/clash-verge-rev |
| **FlClash** | Win/macOS/Linux/Android | ✅ 活跃更新 | https://github.com/chen08209/FlClash |
| **Clash Nyanpasu** | Win/macOS/Linux | ✅ 活跃更新 | https://github.com/keiko233/clash-nyanpasu |
| **Clash Party** | Win/macOS/Linux | ✅ 活跃更新 | https://github.com/YE-2025/clash-party |
| **Mihomo Party** | Win/macOS/Linux | ✅ 活跃更新 | https://github.com/mihomo-party/mihomo-party |
| **ClashX Pro** | macOS | ✅ 维护中 | https://github.com/clashx-pro/ClashX-Pro |
| **Clash Mi** | Android | ✅ 活跃更新 | https://github.com/MetaCubeX/ClashMi |
| **Clash Meta for Android** | Android | ⚠️ 已停更 | https://github.com/MetaCubeX/clashmetaforandroid |
| **Clash for Windows** | Win/macOS/Linux | ❌ 已归档 | https://github.com/Fndroid/clash_for_windows_pkg |
| **ClashN** | Win | ⚠️ 已停更 | https://github.com/2dust/ClashN |

### V2Ray 系列客户端

| 客户端 | 平台 | 状态 | GitHub |
|--------|------|------|--------|
| **V2rayN** | Win | ✅ 活跃更新 | https://github.com/2dust/v2rayN |
| **V2rayNG** | Android | ✅ 活跃更新 | https://github.com/2dust/v2rayNG |
| **V2rayU** | macOS | ✅ 维护中 | https://github.com/yanue/V2rayU |
| **V2rayA** | Linux/Web | ✅ 活跃更新 | https://github.com/v2rayA/v2rayA |

### sing-box 系列客户端

| 客户端 | 平台 | 状态 | GitHub |
|--------|------|------|--------|
| **NekoRay** | Win/Linux | ✅ 活跃更新 | https://github.com/MatsuriDayo/NekoRay |
| **NekoBox** | Android | ✅ 活跃更新 | https://github.com/MatsuriDayo/NekoBox |
| **Hiddify** | 全平台 | ✅ 活跃更新 | https://github.com/hiddify/hiddify-app |
| **Karing** | 全平台 | ✅ 活跃更新 | https://github.com/KaringX/karing |

### iOS 客户端

| 客户端 | 内核 | 价格 | App Store |
|--------|------|------|----------|
| **Shadowrocket** | 多协议 | 付费 | 需外区账号 |
| **Quantumult X** | 多协议 | 付费 | 需外区账号 |
| **Stash** | Mihomo | 付费 | 需外区账号 |
| **Surge** | 原生 | 付费 | 需外区账号 |
| **Loon** | 多协议 | 付费 | 需外区账号 |

### 路由器固件

| 固件/插件 | 平台 | 状态 |
|-----------|------|------|
| **OpenClash** | OpenWrt | ✅ 活跃更新 |
| **MerlinClash** | 梅林固件 | ✅ 维护中 |
| **ShellClash** | Linux路由器 | ✅ 维护中 |

## 🔗 资源汇总

| 类型 | 资源 | 链接 |
|------|------|------|
| 免费节点 | 免费SS/VMess节点 | https://github.com/freefq/free |
| 订阅转换 | subconverter | https://github.com/tindy2013/subconverter |
| 面板管理 | x-ui | https://github.com/vaxilu/x-ui |
| 面板管理 | 3x-ui | https://github.com/MHSanaei/3x-ui |
| 一键脚本 | V2Ray一键安装 | https://github.com/233boy/v2ray |

## ⚠️ 免责声明

本仓库仅供学习和研究使用，请遵守当地法律法规。

**最后更新：** 2026-06-15