# 2026database

班級互動工具與 Firebase Firestore 資料庫工作區。

## 目前狀態

- GitHub repo：<https://github.com/tmje2026-byte/2026database>
- GitHub Pages：<https://tmje2026-byte.github.io/2026database/>
- Firebase project：`my-teaching-tools-31d95`
- Firestore Database：已建立
- Firestore rules：已部署
- 允許讀寫集合：`wordcloud_words`
- Codex 工作模式：已加入 `AGENTS.md`

## 工作節奏

- 開始工作時對 Codex 說：`開工`
- 結束工作時對 Codex 說：`收工`
- 初始化或補缺口時對 Codex 說：`新專案初始化`

## 主要檔案

- `AGENTS.md`：Codex 專案規則
- `firestore.rules`：Firestore 安全規則
- `firebase.json`：Firebase 部署設定
- `.firebaserc`：Firebase project 對應
- `.gitignore`：不要提交的本機與敏感檔案

## 安全原則

- 不提交 `.env`、API key、token、密碼或 Firebase Admin 憑證
- 學生資料只存座號與班級代號，不存真名
- Firebase 前端 config 可以公開，Admin 憑證不可以公開
