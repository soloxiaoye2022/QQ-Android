# QQ for Android Release Archive

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

Archived installers for the Tencent QQ Android client, past and present.

Every file comes from Tencent's official download sources or community archives, unmodified.

## Download

- Latest: [latest release](https://github.com/soloxiaoye2022/QQ-Android/releases/latest)
- Historical: [all releases](https://github.com/soloxiaoye2022/QQ-Android/releases)

## Architectures

| Arch | Notes |
| --- | --- |
| 64bit | arm64-v8a, virtually all modern devices |
| 32bit | armeabi-v7a, older devices |

## File naming

```
QQ-<version>-<arch>.apk
```

Example: `QQ-9.3.85-64bit.apk`

## Verify

Each release ships a `SHA256SUMS` file. On Android use MT Manager or Termux:

```bash
sha256sum QQ-9.3.85-64bit.apk
```

## Install

Allow "install from unknown sources" in system settings.

Downgrading requires uninstalling the newer version first, which wipes local chat history. Back up before you do.

## Provenance

| Source | Coverage |
| --- | --- |
| [A-Randomm-User/APK-save](https://github.com/A-Randomm-User/APK-save) | 8.8.90 through 9.3.80, all versions |
| Tencent official downv6 CDN | Direct links live for the latest build |

## Notes

This repository only mirrors and distributes packages. It provides no modified or cracked clients. The QQ client is copyright Tencent.
