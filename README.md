# 午餐隨機選取小工具 (Lunch Lucky Draw)

這是一個具備現代 Cyberpunk-Glassmorphism 風格的午餐隨機抽籤網頁。旨在解決「午餐吃什麼？」的終極難題。

![午餐抽籤工具介面](https://raw.githubusercontent.com/username/repo-name/main/screenshot.png) <!-- 部署後可更新此連結 -->

## 功能特點

- **極致視覺體驗**：採用毛玻璃效果 (Glassmorphism)、霓虹漸層與流暢的 CSS 動畫。
- **動態清單**：可自由新增自定義午餐選項，並即時刪除。
- **隨機抽取**：具有動態感的抽取動畫，模擬真實抽獎的期待感。
- **響應式設計**：完美支援手機與電腦瀏覽。

---

## 部署到 GitHub Pages 步驟

請依照以下步驟將此專案部署到您的 GitHub 帳號：

### 1. 建立 GitHub 儲存庫 (Repository)

1. 登入您的 [GitHub](https://github.com/) 帳號。
2. 點擊右上角的 `+` 號，選擇 `New repository`。
3. 為儲存庫命名（例如：`lunch-lucky-draw`），設為 `Public`。
4. **不要**勾選 Initialize repository with README (因為我們本地已經有了)。
5. 點擊 `Create repository`。

### 2. 初始化本地 Git 與上傳

在您的專案根目錄開啟終端機 (Terminal/PowerShell)，執行以下指令：

```bash
# 1. 初始化 Git
git init

# 2. 將所有檔案加入暫存區
git add .

# 3. 提交變更
git commit -m "Initial commit: Lunch Lucky Draw App"

# 4. 指定主分支名稱為 main
git branch -M main

# 5. 連結到您剛建立的 GitHub 遠端儲存庫 (請將 <YOUR_USERNAME> 替換為您的帳號)
git remote add origin https://github.com/<YOUR_USERNAME>/lunch-lucky-draw.git

# 6. 推送到 GitHub
git push -u origin main
```

### 3. 開啟 GitHub Pages 服務

1. 回到 GitHub 儲存庫網頁，點擊上方的 `Settings`。
2. 在左側選單中找到 `Code and automation` -> `Pages`。
3. 在 `Build and deployment` -> `Branch` 下方，確保選擇了 `main` 分支與 `/ (root)` 資料夾。
4. 點擊 `Save`。
5. 等待約 1-2 分鐘，GitHub 會顯示您的網址（通常格式為 `https://<YOUR_USERNAME>.github.io/lunch-lucky-draw/`）。

---

## 技術堆疊

- **HTML5**: 語意化結構。
- **CSS3**: 採用 HSL 色彩模型、Backdrop-filter 與 CSS Keyframes。
- **JavaScript**: 純 JS (Vanilla JS) 實作清單管理與抽籤邏輯。

## 開發者資訊

由 Antigravity AI 協助開發。
