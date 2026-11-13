# QQ for Android 历史版本镜像

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

归档腾讯 QQ Android 客户端的历史与最新安装包。

所有文件均取自腾讯官方下载源或社区归档仓库，未做任何修改。

## 其它平台

| 平台 | 仓库 |
| --- | --- |
| Linux | [QQ-Linux](https://github.com/soloxiaoye2022/QQ-Linux) |
| Windows | [QQ-Windows](https://github.com/soloxiaoye2022/QQ-Windows) |
| macOS | [QQ-macOS](https://github.com/soloxiaoye2022/QQ-macOS) |
| Android | 当前 |

## 下载

- 最新版本：[最新 Release](https://github.com/soloxiaoye2022/QQ-Android/releases/latest)
- 历史版本：[全部 Releases](https://github.com/soloxiaoye2022/QQ-Android/releases)

## 架构

| 架构 | 说明 |
| --- | --- |
| 64bit | arm64-v8a，绝大多数现代设备 |
| 32bit | armeabi-v7a，老旧设备 |

## 文件命名

```
QQ-<版本号>-<架构>.apk
```

示例：`QQ-9.3.85-64bit.apk`

## 校验

每个 Release 附带 `SHA256SUMS`。Android 上可用 MT 管理器或 Termux：

```bash
sha256sum QQ-9.3.85-64bit.apk
```

## 安装

需在系统设置中允许「安装未知来源应用」。

若已安装更高版本，需先卸载才能降级安装。降级会清除本地聊天记录，请先备份。

## 版本来源

| 来源 | 覆盖范围 |
| --- | --- |
| [A-Randomm-User/APK-save](https://github.com/A-Randomm-User/APK-save) | 8.8.90 至 9.3.80 全部版本 |
| 腾讯官方 downv6 CDN | 最新版直链可用 |

## 说明

本仓库仅做镜像分发，不提供任何修改或破解版本。QQ 客户端版权归腾讯所有。
