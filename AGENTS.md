# 2026database - AGENTS.md

## 專案入口

專案名稱：2026database
專案用途：班級互動工具與 Firebase Firestore 資料庫工作區
主要工作目錄：G:\我的雲端硬碟\2026database
GitHub repo：https://github.com/tmje2026-byte/2026database
預設 branch：main

## Obsidian 對應筆記

Obsidian vault：C:\Users\User\Documents\Obsidian Vault
專案駕駛艙：2026database/專案工作流程.md
收工時優先更新：同上

> 注意：專案駕駛艙應該是 Obsidian vault 裡的一篇筆記，不是工作資料夾裡的 Markdown 檔。

## 工作桌 + 三個家

- 工作桌：G:\我的雲端硬碟\2026database
- GitHub：https://github.com/tmje2026-byte/2026database
- Obsidian：C:\Users\User\Documents\Obsidian Vault + 2026database/專案工作流程.md
- Firebase：my-teaching-tools-31d95

## 同步規則

開工時：
- 使用 `startup-sync` 流程
- 讀本檔
- 若 Obsidian 駕駛艙已設定，讀駕駛艙
- 檢查 Git 狀態
- 不自動 pull / commit / push

收工時：
- 使用 `shutdown-sync` 流程
- 若 Obsidian 駕駛艙已設定，更新駕駛艙
- 如規則、路徑、專案邊界改變才更新本檔
- 需要時才 commit + push GitHub

新專案初始化時：
- 使用 `project-init-sync` 流程
- 既有設定只補缺口，不覆蓋 Firebase 設定

## 主要檔案

入口檔：`index.html`
設定檔：
- `firebase.json`
- `.firebaserc`
- `firestore.rules`
- `.gitignore`

部署位置：
- Firestore 規則：Firebase project `my-teaching-tools-31d95`
- GitHub Pages：https://tmje2026-byte.github.io/2026database/

## 不要做

- 不要把每日進度寫進 `AGENTS.md`
- 不要自動納入無關 Git 變更
- 不要把 API key、token、密碼寫進 repo
- 不要儲存學生姓名；正式資料只用座號與班級代號
- 不要提交 `.codex/`、`.env`、Admin 憑證或本機私密設定
