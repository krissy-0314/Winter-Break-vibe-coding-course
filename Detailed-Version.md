# 寒假 Vibe Coding 課程資料整理

**課程名稱：** 從開發工具到產品思維  
**講者：** Adam & Hao / 七號演算股份有限公司

---

## Week 1｜單元一：Vibe Coding 入門

### 📋 課程主題
**打造你的第一個 AI 協作專案** — 拆解問題 + 環境建置 + 驗收思維

### 🎯 學習重點

1. **思維升級**
   - 學會將模糊需求拆解為 IPO（輸入 → 處理 → 輸出）
   - Vibe Coding 核心：不是拼命寫 Code，而是精準提問與驗收

2. **建立標準（驗收思維）**
   - 寫程式前，先定義「怎樣才算成功」
   - 黃金法則 3×3：3 個成功案例（Happy Path）+ 3 個失敗案例（Edge Case）

3. **AI 時代的開發迴圈**
   - Prompt（提示）→ Generate（AI 生成）→ Verify（驗證）→ Iterate（迭代）

4. **Vibe Coding 開發流派**
   - Web 免安裝：ChatGPT, Claude, Gemini, Google AI Studio
   - IDE 介面：Cursor, Antigravity
   - 命令列工具：Claude CLI, Gemini CLI

5. **實作任務**
   - 環境準備：安裝 VS Code / Claude Code，建立專案資料夾結構
   - 模擬機台：產生隨機溫度與錯誤碼
   - 邏輯與輸出：加入 If Temp > Threshold 判斷，通過 3×3 測試案例

### 📎 課程資源

| 項目 | 連結 |
|------|------|
| 📊 課堂簡報 | 已提供 PDF |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/ryEiQGN4Wx |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/BkgDazEEWe |
| 🎬 課堂影片 | https://e.lifelong.yzu.edu.tw/course/53 |

### 📝 課後作業
挑選工作中的一個小痛點，寫下它的 IPO 拆解與 3×3 驗收案例。

---

## Week 2｜單元二：Web 小工具快速上線

### 📋 課程主題
**從 IPO 邏輯驗證到 Git 版本控管**

### 🎯 學習重點

1. **Web 工具的兩種型態**
   - 靜態網頁（Static）：HTML+CSS+JS 在瀏覽器端執行，免後端，部署簡單（GitHub Pages）、零成本、快
   - 動態網頁（Dynamic）：需要資料庫與後端伺服器（PHP, Node.js 等），適用會員系統、大型電商

2. **IPO 與驗收標準**
   - Vibe Coding 守則：AI 是工程師，你是 PM
   - I（Input）：輸入什麼？（如：價格、優惠碼）
   - P（Process）：邏輯是什麼？（如：總價 = 單價 × 數量）
   - O（Output）：結果呈現？（如：顯示金額）
   - AC（驗收標準）：明確定義「怎樣才算做完」

3. **TDD（測試驅動開發）思維**
   - 先寫測試（Test），再寫程式（Code）
   - 避免 AI 產出邏輯有洞的程式碼

4. **Git 與 GitHub Desktop**
   - 為什麼需要 Git？紀錄每次修改的「原因」
   - 最重要的功能：當你（或 AI）把程式改壞時，可以一鍵回到過去
   - 實作步驟：Init（初始化）→ Commit（提交）→ Push（推送）
   - 錯誤救援：Revert changes in commit

5. **部署到 GitHub Pages**
   - Settings → Pages → Source 選 main branch → 獲得專屬網址

6. **Chrome Extension 優點**
   - 隨手可得：釘選在瀏覽器右上角
   - 無縫整合：可以直接讀取當前網頁內容

7. **README 的重要性**
   - 給未來的自己看、給接手的人看
   - 最重要：給 AI 看（讓 AI 秒懂專案架構）

### 📎 課程資源

| 項目 | 連結 |
|------|------|
| 📊 課堂簡報 | 已提供 PDF |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/rJIm7HXHWl |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/rkev1IXrbx |
| 🎬 課堂影片 | https://e.lifelong.yzu.edu.tw/course/56 |

### 📝 課後作業
活用目前學過的技巧，做一個可以解決工作痛點的 Web 工具（請提供開發歷程的 prompt）。

---

## Week 3｜單元三：Google Apps Script (GAS) 介紹與應用

### 📋 課程主題
**Google Apps Script 介紹與應用、如何連結 VS Code**

### 🎯 學習重點

1. **GAS 基礎概念**
   - 什麼是 Google Apps Script
   - GAS 與 Google 服務的整合（Sheets, Docs, Gmail 等）

2. **VS Code 連結設定**
   - 如何在本地環境開發 GAS
   - clasp 工具的使用

3. **實作應用**
   - 自動化 Google 試算表操作
   - 建立自訂函數

### 📎 課程資源

| 項目 | 連結 |
|------|------|
| 📊 課堂簡報 | （無 PPT） |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/r1H78_hB-e |
| 🎬 課堂影片 | https://e.lifelong.yzu.edu.tw/course/57 |

---

## Week 4｜單元四：行動指揮中心 LINE Bot 助理

### 📋 課程主題
**打造你的 LINE Bot 助理**

### 🎯 學習重點

1. **LINE Bot 基礎**
   - LINE Messaging API 概念
   - Webhook 設定與運作原理

2. **建立 LINE Bot**
   - LINE Developers 帳號設定
   - Channel 建立與設定

3. **整合應用**
   - 結合前幾週學到的技術
   - 打造個人化的 LINE Bot 助理

### 📎 課程資源

| 項目 | 連結 |
|------|------|
| 📊 課堂簡報 | 已提供 PPTX |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/HykF71LLZx |
| 🎬 課堂影片 | https://e.lifelong.yzu.edu.tw/course/58 |

---

## Week 5｜單元五：爬蟲技術介紹

### 📋 課程主題
**網頁爬蟲技術入門**

### 🎯 學習重點

1. **爬蟲基礎概念**
   - 什麼是網頁爬蟲
   - 爬蟲的應用場景

2. **爬蟲技術實作**
   - HTML 結構解析
   - 資料擷取方法

3. **注意事項**
   - 爬蟲的法律與道德考量
   - robots.txt 規範

### 📎 課程資源

| 項目 | 連結 |
|------|------|
| 📊 課堂簡報 | （無 PPT） |
| 📝 操作手冊 (HackMD) | https://hackmd.io/@vVHC1jffQWuFZd6HVu7sFg/BkcpQ7kvbx |
| 🎬 課堂影片 | （待放） |

---

## 📚 課程資源總覽

| 週次 | 單元主題 | 簡報 | HackMD | 影片 |
|:----:|----------|:----:|:------:|:----:|
| Week 1 | Vibe Coding 入門 | ✅ | ✅ | ✅ |
| Week 2 | Web 小工具快速上線 | ✅ | ✅ | ✅ |
| Week 3 | GAS 介紹與應用 | ❌ | ✅ | ✅ |
| Week 4 | LINE Bot 助理 | ✅ | ✅ | ✅ |
| Week 5 | 爬蟲技術介紹 | ❌ | ✅ | 待放 |

---

## 🔑 課程核心概念

### Vibe Coding 開發流程
```
1. Spec (Input/Output) → 2. AI (TDD 測試驅動開發) → 3. Validate (人眼+自動測試) → 4. Git (版本存檔) → 5. Deploy (Web/Extension)
```

### IPO 思維框架
- **I (Input)**: 輸入什麼資料？
- **P (Process)**: 處理邏輯是什麼？
- **O (Output)**: 預期輸出什麼結果？
- **AC (Acceptance Criteria)**: 驗收標準 3×3（3 成功 + 3 失敗案例）

---

*文件整理日期：2026/02/03*
