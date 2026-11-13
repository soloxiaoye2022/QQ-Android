# QQ for Android 歷史版本鏡像

[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [English](README.en.md)

歸檔騰訊 QQ Android 客戶端的歷史與最新安裝包。

所有檔案均取自騰訊官方下載源或社群歸檔倉庫，未做任何修改。

## 其它平台

| 平台 | 倉庫 |
| --- | --- |
| Linux | [QQ-Linux](https://github.com/soloxiaoye2022/QQ-Linux) |
| Windows | [QQ-Windows](https://github.com/soloxiaoye2022/QQ-Windows) |
| macOS | [QQ-macOS](https://github.com/soloxiaoye2022/QQ-macOS) |
| Android | 當前 |

## 下載

- 最新版本：[最新 Release](https://github.com/soloxiaoye2022/QQ-Android/releases/latest)
- 歷史版本：[全部 Releases](https://github.com/soloxiaoye2022/QQ-Android/releases)

## 架構

| 架構 | 說明 |
| --- | --- |
| 64bit | arm64-v8a，絕大多數現代裝置 |
| 32bit | armeabi-v7a，老舊裝置 |

## 檔案命名

```
QQ-<版本號>-<架構>.apk
```

範例：`QQ-9.3.85-64bit.apk`

## 校驗

每個 Release 附帶 `SHA256SUMS`。Android 上可用 MT 管理器或 Termux：

```bash
sha256sum QQ-9.3.85-64bit.apk
```

## 安裝

需在系統設定中允許「安裝未知來源應用」。

若已安裝更高版本，需先解除安裝才能降級。降級會清除本機聊天記錄，請先備份。

## 版本來源

| 來源 | 涵蓋範圍 |
| --- | --- |
| [A-Randomm-User/APK-save](https://github.com/A-Randomm-User/APK-save) | 8.8.90 至 9.3.80 全部版本 |
| 騰訊官方 downv6 CDN | 最新版直連可用 |

## 說明

本倉庫僅做鏡像分發，不提供任何修改或破解版本。QQ 客戶端版權歸騰訊所有。
