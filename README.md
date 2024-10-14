<a href="https://alfo0924.github.io/GetBTCPriceWebDescription/">作品說明頁</a>

## 架設CPI網站

### 準備工作

1. 使用Jina AI進行網站分析
   - 選擇Reader功能
   - 輸入要分析的網站
   - 點擊"Fetch Content"抓取網站資料
   - 詢問AI關於網站如何抓取/使用API並生成HTML

### 環境設置

1. 在IDE中建置Express.js環境
   - 設置ViewEngine參數為none

2. 安裝SQLite數據庫套件
   - 在終端機輸入: `npm install sqlite3 --save`
   - 確認package.json中dependencies包含 `"sqlite3": "^5.1.7"`

### 數據處理

1. 從數據來源網站下載數據文件
2. 使用在線SQLite數據庫工具
   - 將數據文件導入在線數據庫
   - 選擇適當的欄位名稱
   - 確認新增的BTC/USD表格
   - 查看編輯語法記錄和SQL語法
3. 保存數據庫文件到本地計算機
   - 在專案路徑創建"db"文件夾
   - 將數據庫文件放入該文件夾

### 代碼開發

1. 複製數據庫SQL語法
2. 詢問AI如何串接HTML、app.js和JSON
3. 提供專案路徑、後端代碼、前端代碼和SQL語法給AI以獲得更好的理解和建議

### 文件結構調整

- 將index.html從public文件夾移出，以便GitHub能夠正確識別

### 部署準備

1. 確認本地端可以正確抓取數據庫數據
2. 將文件推送更新到GitHub

### Render部署

1. 在Render註冊帳號
2. 創建新的Web Service
3. 連接到GitHub Repository
4. 選擇要部署的專案Repository
5. 完成部署後，查看狀態列和專案部署網址


