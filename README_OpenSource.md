[BilldDesk Pro](./README.md) | BilldDesk 開源版

<p align="center">
  <a href="https://desk.hsslive.cn" target="_blank">
    <img
      width="200"
      src="https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/icon.png"
    />
  </a>
</p>

<h1 align="center">
  BilldDesk
</h1>

<p align="center">
  基於Vue3 + WebRTC + Nodejs + Electron + Flutter搭建的桌面控制（win、mac、安卓）
</p>

<div align="center">

![stars](https://img.shields.io/github/stars/galaxy-s10/billd-desk)
![forks](https://img.shields.io/github/forks/galaxy-s10/billd-desk)

![version](https://img.shields.io/github/package-json/v/galaxy-s10/billd-desk)
![License](https://img.shields.io/github/license/galaxy-s10/billd-desk)
![language](https://img.shields.io/github/languages/top/galaxy-s10/billd-desk)
![language](https://img.shields.io/github/languages/top/galaxy-s10/billd-desk-server)
![language](https://img.shields.io/github/languages/top/galaxy-s10/billd-desk-flutter)

</div>

## ⭐️ BilldDesk

> [!CAUTION]
> BilldDesk 目前仍未釋出穩定版，不建議開發者用於生產環境！

## ⚡️ BilldDesk Pro

BilldDesk存在兩個已知問題（許可權，控制）在現有架構下，幾乎不可修復！為什麼不可修復？看我發的b站影片：[https://www.bilibili.com/video/BV1yqN9zsEEd?vd_source=bf386c933a4aff3e8b19a1f003de0015&p=2&spm_id_from=333.788.videopod.sections](https://www.bilibili.com/video/BV1yqN9zsEEd?vd_source=bf386c933a4aff3e8b19a1f003de0015&p=2&spm_id_from=333.788.videopod.sections)，01:35秒開始到20:45秒。

`BilldDeskPro` 完全重寫了`BilldDesk`，修復了`BilldDesk`的已知問題（許可權，控制）。並且穩定性更高、效能更強、程式碼可讀性更好、更新更頻繁

BilldDeskPro客戶端下載：

- github release：[https://github.com/galaxy-s10/billd-desk/releases/tag/v0.76.0](https://github.com/galaxy-s10/billd-desk/releases/tag/v0.76.0)
- 官網下載：[https://desk.hsslive.cn/#/download](https://desk.hsslive.cn/#/download)

> BilldDeskPro訂閱：[https://desk.hsslive.cn/#/price](https://desk.hsslive.cn/#/price)

## 簡介

BilldDesk 遠端桌面控制，目前實現了類似 ToDesk、向日葵等遠端桌面的功能。

## 對比ToDesk

> 作者使用過很多遠端軟體：TeamViewer、向日葵、ToTesk、AnyDesk、RustDesk、UU遠端、連連控，還有qq自帶的遠端協助等等，但用ToDesk比較多，因此用ToTesk和BilldDesk作對比~

|                           | BilldDesk    | BilldDesk Pro    | ToDesk                                                 |
| ------------------------- | ------------ | ---------------- | ------------------------------------------------------ |
| 連線限制                  | 無限制，免費 | 無限制，免費     | 80h/月，200次/月，24h/次，超出需要購買專業版（¥24/月） |
| 畫質限制                  | 無限制，免費 | 限制1080p，免費  | 限制1080p，免費                                        |
| 幀率限制                  | 無限制，免費 | 限制60幀，免費   | 限制30幀，免費                                         |
| 安卓被控                  | 不支援       | 支援，免費       | 支援，需要購買專業版（¥24/月）或購買外掛（¥15/月）     |
| 自定義裝置碼              | 支援，免費   | 支援，免費       | 不支援                                                 |
| 裝置分組管理              | 支援，免費   | 支援，免費       | 支援，免費                                             |
| 開機自啟/無人值守         | 不支援       | 支援，免費       | 支援，免費                                             |
| 隱私屏                    | 不支援       | 支援，免費       | 支援，需要購買專業版（¥24/月）                         |
| 虛擬屏                    | 不支援       | 支援，免費       | 支援，需要購買效能版（¥95/月）                         |
| 遠端時錄屏                | 不支援       | 支援，免費       | 不支援                                                 |
| 螢幕牆                    | 不支援       | 支援，階梯收費   | 支援，需要購買技術版（¥218/月）                        |
| 批次群控                  | 不支援       | 支援，螢幕牆自帶 | 不支援                                                 |
| web網頁發起遠端控制       | 支援，免費   | 支援，免費       | 支援，需要購買專業版（¥24/月）                         |
| 後臺管理                  | 不支援       | 支援，免費       | 支援，免費                                             |
| 遠端控制web網頁（僅觀看） | 支援，免費   | 支援，免費       | 不支援                                                 |
| 同賬號多主控同時發起遠控  | 支援，免費   | 支援，免費       | 支援，需要購買外掛（¥233/月）                          |
| 私有化部署/二次開發       | 支援，免費   | 支援，付費       | 支援，需要ToDesk企業版，定價未知                       |

## 生態

| 專案名稱            | 程式碼倉庫                                                               | star & fork                                                                                                                                                                                                                                                                                                     | 線上地址/下載地址                                                        |
| ------------------- | ---------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------ |
| 遠端桌面網頁/客戶端 | [billd-desk](https://github.com/galaxy-s10/billd-desk)                 | [![github](https://img.shields.io/github/stars/galaxy-s10/billd-desk?label=star&logo=GitHub)](https://github.com/galaxy-s10/billd-desk) [![github](https://img.shields.io/github/forks/galaxy-s10/billd-desk?label=fork&logo=GitHub)](https://github.com/galaxy-s10/billd-desk)                                 | [https://desk.hsslive.cn](https://desk.hsslive.cn)                       |
| 遠端桌面後臺        | [billd-desk-admin](https://github.com/galaxy-s10/billd-desk-admin)     | [![github](https://img.shields.io/github/stars/galaxy-s10/billd-desk-admin?label=star&logo=GitHub)](https://github.com/galaxy-s10/billd-desk) [![github](https://img.shields.io/github/forks/galaxy-s10/billd-desk-admin?label=fork&logo=GitHub)](https://github.com/galaxy-s10/billd-desk-admin)               | [https://desk-admin.hsslive.cn](https://desk-admin.hsslive.cn)           |
| 遠端桌面移動端      | [billd-desk-flutter](https://github.com/galaxy-s10/billd-desk-flutter) | [![github](https://img.shields.io/github/stars/galaxy-s10/billd-desk-flutter?label=star&logo=GitHub)](https://github.com/galaxy-s10/billd-desk-flutter) [![github](https://img.shields.io/github/forks/galaxy-s10/billd-desk-flutter?label=fork&logo=GitHub)](https://github.com/galaxy-s10/billd-desk-flutter) | [https://desk.hsslive.cn/#/download](https://desk.hsslive.cn/#/download) |
| 遠端桌面服務端      | [billd-desk-server](https://github.com/galaxy-s10/billd-desk-server)   | [![github](https://img.shields.io/github/stars/galaxy-s10/billd-desk-server?label=star&logo=GitHub)](https://github.com/galaxy-s10/billd-desk-server) [![github](https://img.shields.io/github/forks/galaxy-s10/billd-desk-server?label=fork&logo=GitHub)](https://github.com/galaxy-s10/billd-desk-server)     | [https://desk-api.hsslive.cn](https://desk-api.hsslive.cn)               |

## 功能

- [x] `web網頁` 控制 `電腦端`
- [x] `web網頁` 控制 `安卓端`
- [x] `web網頁` 控制 `web網頁`（僅觀看）
- [x] `電腦端` 控制 `電腦端`
- [x] `電腦端` 控制 `安卓端`
- [x] `電腦端` 控制 `web網頁`（僅觀看）
- [ ] `安卓端` 控制 `電腦端`
- [ ] `安卓端` 控制 `安卓端`
- [ ] `安卓端` 控制 `web網頁`（僅觀看）
- [x] 多臺裝置同時遠端一臺裝置
- [x] 一臺裝置同時遠端多臺裝置
- [x] 多屏操作
- [x] 連線鑑權
- [x] 自定義裝置碼/連線密碼
- [x] 自定義介面（wws/api/中繼伺服器）
- [x] 按鍵組合鍵
- [x] 檔案傳輸
- [x] 開機自啟
- [x] 鎖屏保活
- [x] 螢幕牆
- [x] 批次群控
- [x] 隱私屏
- [x] 虛擬屏
- [x] 擴充套件屏
- [x] 裝置分組
- [x] 支援 macOS 系統
- [x] 支援 Windows 系統
- [ ] 支援 Linux 系統
- [x] 支援 安卓端（Flutter）
- [ ] 支援 蘋果端（Flutter）
- [x] 後臺管理
- [ ] Docker一鍵部署
- [x] 支援私有化部署

## 預覽

快速體驗：[https://desk.hsslive.cn](https://desk.hsslive.cn)

### web網頁/電腦端控制電腦端

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/111.png?raw=true)

### web網頁/電腦端控制安卓端

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/222.png?raw=true)

### web網頁/電腦端控制web網頁

> 僅觀看模式

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/333.png?raw=true)

### web網頁移動端

> 首頁

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/777.png?raw=true)

> 控制頁

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/888.png?raw=true)

### 螢幕牆

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/444.png?raw=true)

### 批次群控

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/b1.webp?raw=true)

### 裝置分組

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/999.png?raw=true)

### 隱私屏

> 支援自定義隱私屏（圖片、文字）

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a7.png?raw=true)

### 虛擬屏

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a8.png?raw=true)

### 滑鼠、鍵盤模擬

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a9.jpg?raw=true)

### 安卓端控制電腦端【TODO】

### 安卓端控制安卓端【TODO】

### 安卓端控制web網頁【TODO】

> 僅觀看模式

### 檔案傳輸

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/666.png?raw=true)

### 跨平臺支援

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/555.png?raw=true)

### [後臺] 控制檯

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a2.png?raw=true)

### [後臺] 黑名單

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a1.png?raw=true)

### [後臺] 裝置分組

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a3.png?raw=true)

### [後臺] 遠端管理

- 遠端記錄

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a4.png?raw=true)

- 線上遠端

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a5.png?raw=true)

- 線上裝置

![img](https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/a6.png?raw=true)

## 技術棧

- 前端相關：[Vue3](https://vuejs.org) 以及相關技術棧、`Typescript`、`WebRTC`、`WebCodecs`、`Web Workder`、`Web Audio`、`Canvas`
- 後端相關：[Nodejs](https://nodejs.org) 以及相關技術棧、`Koa2`、`Typescript`、`Sequelize`、`Mysql`、`Redis`、`Socket.io`
- 桌面客戶端相關：[Electron](https://www.electronjs.org)以及相關技術棧、`WebRTC`
- 移動客戶端相關：[Flutter3](https://flutter.dev)以及相關技術棧、`WebRTC`
- 流媒體伺服器相關：[SRS](https://ossrs.net)、 [FFmpeg](https://ffmpeg.org)、[Coturn](https://github.com/coturn/coturn)
- Docker 相關：[Docker](https://www.docker.com)
- 部署相關：[阿里云云效](https://devops.aliyun.com)、[billd-deploy](https://github.com/galaxy-s10/billd-deploy)

## 本地啟動

- [x] billd-desk(pro) 檢視 [start-client.md](https://github.com/galaxy-s10/billd-desk/blob/main/doc/start-client.md)

## 介面文件

檢視 [apifox](https://apifox.com/apidoc/shared-a8ba9715-7730-432d-896c-97f983050795)

## 效能測試

檢視 [benchmarking.md](https://github.com/galaxy-s10/billd-desk/blob/main/doc/benchmarking.md)

## 常見問題

[https://desk.hsslive.cn/#/faq](https://desk.hsslive.cn/#/faq)

## 問題反饋

歡迎提 [issue](https://github.com/galaxy-s10/billd-desk/issues)

## 參與貢獻

歡迎提 [pr](https://github.com/galaxy-s10/billd-desk/pulls)

## 私有化部署

billd-desk完全開源（可商用），歡迎部署！

## 客戶端下載

[https://desk.hsslive.cn/#/download](https://desk.hsslive.cn/#/download)

## 官方交流群

- [交流群（使用者）.md](https://github.com/galaxy-s10/billd-desk/blob/main/doc/交流群（使用者）.md)
- [交流群（開發）.md](https://github.com/galaxy-s10/billd-desk/blob/main/doc/交流群（開發）.md)

## 多平臺支援

- [x] Web網頁（建議使用：[Chrome瀏覽器](https://www.google.com/intl/zh-CN/chrome/) / [Via瀏覽器](https://viayoo.com) / `Safari瀏覽器`）
- [ ] Windows 7 不支援
- [x] Windows 10、Windows 11
- [x] Windows Server 2022，其他版本未實際測試
- [x] macOS
- [x] Linux
- [x] Android 11 至 Android 15，其他版本未實際測試
- [ ] iOS

## 貢獻者

  <a href="https://github.com/galaxy-s10/billd-desk/graphs/contributors" target="_blank">
    <img
      width="200"
      src="https://contrib.rocks/image?repo=galaxy-s10/billd-desk"
      alt="BilldDesk logo"
    />
  </a>

## 初心

該專案初心只是作為[billd-live](https://github.com/galaxy-s10/billd-live)的衍生專案，但後面覺得遠端桌面也挺有意思的，就一直堅持完善下去。

## 願景

各大遠端軟體雖然免費都能用，但免費版的功能覆蓋不夠全面，比如有些普通個人使用者可能只是臨時需要遠端一下安卓手機，但卻需要開通一個月的服務才可以。BilldDesk完善了這些基本功能，讓普通使用者也能用上~
