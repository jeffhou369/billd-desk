BilldDesk Pro | [BilldDesk 開源版](./README_OpenSource.md)

<p align="center">
  <a href="https://desk.hsslive.cn" target="_blank">
    <img
      width="200"
      src="https://github.com/galaxy-s10/billd-desk/blob/main/readme_img/icon.png"
    />
  </a>
</p>

<h1 align="center">
  BilldDesk Pro
</h1>

<p align="center">
  跨平臺遠端桌面控制，實現了類似 ToDesk/向日葵等遠端軟體的功能。
</p>

## 實測

- [x] 支援2K + 60 Fps
  - [x] 被控端：系統：Windows 10，顯示卡：NVIDIA GeForce RTX 3060 Laptop
  - [x] 主控端：Chrome瀏覽器/BilldDesk客戶端
- [x] 支援2K + 120 Fps
  - [x] 被控端：系統：Windows 11，顯示卡：NVIDIA GeForce RTX 5070
  - [x] 主控端：Chrome瀏覽器/BilldDesk客戶端
- [x] 支援1080P + 60 Fps
  - [x] 被控端：系統：Windows 10，顯示卡：NVIDIA GeForce RTX 2070 Laptop
  - [x] 主控端：Chrome瀏覽器/BilldDesk客戶端
- [x] 支援1080P + 60 Fps
  - [x] 被控端：系統：Windows 10，顯示卡：NVIDIA GeForce GTX 1060 6G
  - [x] 主控端：Chrome瀏覽器/BilldDesk客戶端

## 功能

- [x] `web網頁` 控制 `電腦端`
- [x] `web網頁` 控制 `安卓端`
- [x] `web網頁` 控制 `web網頁`（僅觀看）
- [x] `電腦端` 控制 `電腦端`
- [x] `電腦端` 控制 `安卓端`
- [x] `電腦端` 控制 `web網頁`（僅觀看）
- [x] `安卓端` 控制 `電腦端`
- [x] `安卓端` 控制 `安卓端`
- [x] `安卓端` 控制 `web網頁`（僅觀看）
- [x] 硬體加速
  - [x] 開啟/關閉編碼硬體加速
  - [x] 開啟/關閉解碼硬體加速
  - [x] 開啟/關閉零複製
  - [x] NVIDIA顯示卡（H264/H265/AV1），顯示卡要求十代以上、顯示卡驅動需要570.0+版本
  - [x] AMD顯示卡（H264/H265/AV1）
  - [x] Intel集顯（H264/H265/AV1）
  - [x] Apple VideoToolbox（H264）
- [x] 主流編解碼協議
  - [x] H264/H265
  - [x] AV1
  - [x] VP8/VP9
- [x] 隱私屏（Windows、macOS）
  - [x] 自定義隱私屏圖片
  - [x] 自定義隱私屏文字
- [x] 虛擬屏
  - [ ] Windows，藉助[parsec-vdd](https://github.com/nomi-san/parsec-vdd)
  - [ ] macOS，藉助[Crisp](https://github.com/didriksg/Crisp)/[BetterDisplay](https://github.com/waydabber/BetterDisplay)
- [x] 虛擬音效卡
  - [x] Windows，藉助[VB-CABLE](https://vb-audio.com/Cable/index.htm)
  - [x] macOS，藉助[BlackHole](https://github.com/ExistentialAudio/BlackHole)
- [x] 驅動級鍵鼠（避免遊戲風控）
- [x] 滑鼠模式
  - [x] 使用主控端滑鼠
  - [x] 使用被控端滑鼠（fps遊戲）
  - [x] 智慧滑鼠
- [x] 螢幕牆
  - [x] 支援Windows/macOS/Android
  - [x] 支援單控
  - [x] 支援群控
- [x] 多臺裝置同時遠端一臺裝置
- [x] 一臺裝置同時遠端多臺裝置
- [x] 多屏操作
- [x] 連線鑑權
- [x] 自定義裝置碼/連線密碼
- [x] 自定義中繼伺服器
- [x] 自定義介面（wss、api）
- [x] 位元速率/幀率/畫質調整
- [x] 按鍵對映
- [x] 剪貼簿同步
- [x] 解析度同步
- [x] 檔案傳輸
  - [x] 主控->被控
  - [x] 主控<-被控
- [x] 文字互動
- [x] 本機被控結束後鎖屏
- [x] 僅允許同賬號遠端
- [x] 遠端開機（WOL）
- [x] 遠端更新客戶端版本（Windows）
- [x] 系統托盤
- [x] 開機自啟（無人值守）
- [x] 程序保活（Windows）
- [x] 線上更新/主控端遠端更新被控端（Windows）
- [x] 幀率模式
  - [x] 根據畫面變化，智慧降幀率，最佳化頻寬佔用
- [x] 網路模式
  - [x] 預設
  - [x] 低延遲
- [x] 快捷鍵/常用操作
  - [x] Ctrl+Alt+Del
  - [x] 顯示桌面
  - [x] 開啟設定
  - [x] 任務檢視
  - [x] 工作管理員
  - [x] 資源管理器
  - [x] 重啟
  - [x] 關機
  - [x] 登出
  - [x] 鎖定
- [x] 批次群控
- [x] 裝置分組
- [x] 後臺管理
- [x] 私有化部署
- [ ] Docker一鍵部署

## 對比ToDesk

> 作者使用過很多遠端軟體：TeamViewer、向日葵、ToTesk、AnyDesk、RustDesk、UU遠端、連連控，還有qq自帶的遠端協助等等，但用ToDesk比較多，因此用ToTesk和BilldDesk作對比~

|                                        | BilldDesk    | BilldDesk Pro                                     | ToDesk                                                 |
| -------------------------------------- | ------------ | ------------------------------------------------- | ------------------------------------------------------ |
| 連線限制                               | 無限制，免費 | 無限制，免費                                      | 80h/月，200次/月，24h/次，超出需要購買專業版（¥24/月） |
| 畫質限制                               | 無限制，免費 | 限制1080p，免費                                   | 限制1080p，免費                                        |
| 幀率限制                               | 無限制，免費 | 限制30幀，免費                                    | 限制30幀，免費                                         |
| 安卓被控                               | 不支援       | 支援，免費                                        | 支援，需要購買專業版（¥24/月）或購買外掛（¥15/月）     |
| 自定義裝置碼                           | 支援，免費   | 支援，免費                                        | 不支援                                                 |
| 裝置分組管理                           | 支援，免費   | 支援，免費                                        | 支援，免費                                             |
| 開機自啟/無人值守                      | 不支援       | 支援，免費                                        | 支援，免費                                             |
| 隱私屏                                 | 不支援       | 支援，免費                                        | 支援，需要購買專業版（¥24/月）                         |
| 虛擬屏                                 | 不支援       | 支援，免費                                        | 支援，需要購買效能版（¥95/月）                         |
| 遠端時錄屏                             | 不支援       | 支援，免費                                        | 不支援                                                 |
| 螢幕牆                                 | 不支援       | 支援，階梯收費                                    | 支援，需要購買技術版（¥218/月）                        |
| 批次群控                               | 不支援       | 支援，螢幕牆自帶                                  | 不支援                                                 |
| web網頁發起遠端控制                    | 支援，免費   | 支援，免費                                        | 支援，需要購買專業版（¥24/月）                         |
| 後臺管理                               | 不支援       | 支援，免費                                        | 支援，免費                                             |
| 遠端控制web網頁（僅觀看）              | 支援，免費   | 支援，免費                                        | 不支援                                                 |
| 通道數限制（同賬號多主控同時發起遠控） | 無限制，免費 | 無限制，免費                                      | 限制1個，增加需要購買外掛（¥233/月）                   |
| 私有化部署/二次開發                    | 支援，免費   | 支援，[訂閱原始碼](https://desk.hsslive.cn/#/price) | 支援，需要ToDesk企業版，定價未知                       |

## 跨平臺支援

- [x] Windows 系統
  - [x] Windows 10、Windows 11
  - [x] Windows Server 2022
  - [x] Windows Server 2019
  - [ ] Windows 7 不支援
  - [ ] 其他版本未實際測試
- [x] macOS 系統
  - [x] macOS 15
  - [ ] 其他版本未實際測試
- [x] Android系統
  - [x] Android 8 至 Android 16
  - [x] Android 7，被控時支援觀看，暫不支援操作
  - [ ] ~~Android 6，不再支援安卓6~~
  - [ ] 其他版本未實際測試
- [x] Web瀏覽器（[Chrome](https://www.google.com/intl/zh-CN/chrome/)、[Edge](https://www.microsoft.com/zh-cn/edge/download)、[Firefox](https://www.firefox.com/zh-CN/)、[Via](https://viayoo.com)、[Safari](https://www.apple.com/safari/)）
- [ ] iOS系統
- [ ] Linux 系統

## 技術架構

框架/第三方庫：

- Flutter
- Vue
- Koa2
- ...

程式語言：

- JavaScript/Typescript
- Dart
- Kotlin
- C++
- Swift
- ...

Api：

- WebRTC
- Win32
- Cocoa
- AccessibilityService
- ...

## 客戶端下載

[https://desk.hsslive.cn/#/download](https://desk.hsslive.cn/#/download)

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

### 安卓端控制電腦端

### 安卓端控制安卓端

### 安卓端控制web網頁

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

## BilldDesk Pro免費嗎？

- **免費**，你可以直接下載BilldDesk客戶端，開始流暢的遠端體驗。
- 有付費功能（隱私屏、虛擬屏、螢幕牆、高位元速率/幀率/畫質），如果你經常使用到BilldDesk，推薦你購買任意VIP套餐（包月6元/月、包年4.2元/月）。

## 常見問題

[https://desk.hsslive.cn/#/faq](https://desk.hsslive.cn/#/faq)

## 問題反饋

歡迎提 [issue](https://github.com/galaxy-s10/billd-desk/issues)

## 聯絡作者

[https://desk.hsslive.cn/#/hi](https://desk.hsslive.cn/#/hi)

## BilldDesk Pro原始碼

- BilldDesk開源：[原始碼](./README_OpenSource.md)
- BilldDesk Pro不開源，原始碼需要購買：[https://desk.hsslive.cn/#/price](https://desk.hsslive.cn/#/price)
