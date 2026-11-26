## billd-desk(pro)

## 安裝依賴

> 使用 node 版本：v18.19.0，建議18版本
> 使用 pnpm 版本：9.1.3，建議9版本

```bash
pnpm i
```

> 更新 billd 相關依賴：

```bash
pnpm i billd-deploy@latest billd-utils@latest billd-scss@latest billd-html-webpack-plugin@latest
```

## 執行

> 配置檔案：**`src/spec-config.ts`**，請在該檔案填寫對應的資訊。

```bash
npm run dev
```

## 打包

> 打包時會先使用[`standard-version`](https://github.com/conventional-changelog/standard-version#readme)進行發版，請確保當前專案初始化了 git，否則打包會失敗。

- web

> 打包成功後，資源輸出在`dist`目錄

```bash
npm run build:web
```

- windows、macos、linux 包

> 打包成功後，資源輸出在`electron-release`目錄

```bash
npm run build
```

- windows 包

> 打包成功後，資源輸出在`electron-release`目錄

```bash
npm run build:win
```

- macos 包

> 打包成功後，資源輸出在`electron-release`目錄

```bash
npm run build:mac
```

- linux 包

> 打包成功後，資源輸出在`electron-release`目錄

```bash
npm run build:linux
```
