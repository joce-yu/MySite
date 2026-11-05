# Judy.Dev – Personal Portfolio Website

個人履歷暨作品集網站，展示個人軟體開發經驗、核心技術、專案成果及聯絡資訊。

本專案以 **HTML、CSS、JavaScript** 建置響應式個人網站，呈現全端軟體工程師的技術能力與實務開發經驗。

---

## 📌 專案介紹（Introduction）

Judy.Dev 是一個個人履歷與作品集網站（Personal Portfolio Website），主要用於展示個人工作經歷、技術專長、專案成果及社群資訊。

網站以深色系科技風格為設計主軸，提供簡潔且具互動性的瀏覽體驗，方便企業招募人員及開發者快速了解個人技術背景。

## ✨ 功能特色（Features）

- **個人介紹（About Me）**
  - 個人簡介與軟體開發經驗
  - 技術背景與專業領域展示

- **核心技術（Tech Stack）**
  - 後端開發技術
  - 前端開發技術
  - 系統整合與自動化技術

- **專案成果（Projects）**
  - POS 軟體授權控制系統
  - 線上金流串接與自動延展授權機制
  - 系統運作流程展示

- **互動式使用者介面（UI / UX）**
  - RWD 響應式網頁設計
  - 深色 / 淺色模式切換
  - 手機版導覽選單
  - 頁面滾動淡入動畫

- **背景音樂播放器（Background Music）**
  - 背景音樂播放與暫停
  - 音樂播放狀態動畫

- **聯絡表單（Contact Form）**
  - 姓名、Email、訊息欄位
  - 透過 Google Apps Script 接收表單資料
  - 將聯絡資訊寫入 Google 試算表

## 🛠️ 使用技術（Tech Stack）

| 類別 | 技術 |
|---|---|
| Front-End | HTML5 |
| Styling | CSS3 |
| JavaScript | Vanilla JavaScript |
| CSS Framework | Tailwind CSS |
| Icons | Lucide Icons |
| Responsive Design | RWD |
| Form Integration | Google Apps Script |
| Data Storage | Google Sheets |

### 使用的第三方資源

- Tailwind CSS CDN
- Lucide Icons
- Pixabay Background Music

## 📂 專案結構（Project Structure）

```text
Judy-Portfolio/
│
├── index.html          # 網站主要頁面
└── README.md           # 專案說明文件
```

目前網站主要內容、CSS 樣式及 JavaScript 程式碼皆整合於 `index.html`。

## 🚀 如何執行（Getting Started）

本專案為前端靜態網站，不需要安裝後端環境或額外建置工具。

### 1. Clone Repository

```bash
git clone https://github.com/你的GitHub帳號/你的Repository名稱.git
```

### 2. 開啟專案

進入專案資料夾，直接使用瀏覽器開啟：

```text
index.html
```

即可瀏覽個人履歷網站。

### 3. GitHub Pages 部署

本專案支援透過 GitHub Pages 部署靜態網站。

1. 進入 GitHub Repository。
2. 開啟 Settings。
3. 選擇 Pages。
4. 在 Build and deployment 設定中選擇 Deploy from a branch。
5. 選擇 `main` 分支及 `/ (root)` 資料夾。
6. 儲存設定，等待 GitHub Pages 部署完成。

部署完成後，即可透過 GitHub Pages 提供的網址公開瀏覽。

## ⚙️ 設定說明（Configuration）

若要將本專案作為自己的個人作品集，建議修改以下內容：

- 個人姓名及自我介紹。
- 工作經驗與技術專長。
- 專案成果及專案說明。
- 個人照片及社群連結。
- 聯絡表單使用的 Google Apps Script Web App URL。
- SEO Meta Tags 與網站網址。

## 📬 聯絡表單（Contact Form）

網站聯絡表單使用 Google Apps Script 作為資料接收端，透過 JavaScript Fetch API 傳送資料，並將聯絡資訊儲存至 Google Sheets。

表單欄位包含：

- Name：聯絡人姓名
- Email：聯絡人電子郵件
- Message：訊息內容

如需使用聯絡表單功能，必須自行設定並部署 Google Apps Script Web App。

## 📄 License

本專案目前未指定開源授權條款（License）。

