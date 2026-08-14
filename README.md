# 每日追蹤事項（世界島社區管委會）

管委會每日追蹤事項的手機網頁前端。開啟：https://austinweng.github.io/daily-todo/

- 這裡只放靜態頁面（build artifact）；**程式碼正本**在私有 repo `AustinWeng/Claude` 的
  `plugins/daily-todo/skills/每日追蹤網頁/`，勿直接改這份
- 資料經 Cloud Run API 讀寫 Google Drive 上的「每日追蹤事項.xlsx」
- 更新方式：在正本資料夾執行 `./deploy_pages.sh`
