# 張梓閎｜Backend / Software / AI Intern

🎓 國立高雄大學 資訊管理學系（2022/09 – 2026/06）  
📍 新北市淡水區｜可配合台北／新北／高雄  
📧 Email: mark20031122@gmail.com  
📱 Phone: 0975-901-492  
🔗 GitHub: https://github.com/你的帳號

---

## 👋 About Me

我是張梓閎，目前就讀於國立高雄大學資訊管理學系四年級，對**程式設計、系統開發與技術學習**抱有高度熱情。

我做事風格偏向**穩健、踏實與理性分析**，在團隊中常扮演讓事情順利推進的角色，例如：
- 整理需求與資訊
- 協助釐清問題核心
- 將零散想法整合成可執行方案

面對任務時，我不只追求完成，而是希望能夠把事情做好；遇到問題會耐心追查原因並逐步解決，也能在突發狀況下保持冷靜與穩定。

---

## 💡 Interests & Motivation

- 熱愛程式設計與技術實作
- 享受分析問題、拆解問題與解決問題的過程
- 樂於嘗試新工具、新技術，並應用於實際專案中

希望能透過實習累積實務經驗，強化抗壓性與應變能力，將每一次挑戰轉化為成長的養分。

---

## 🛠 Skills

### Programming Languages
- **Python**
- **Java**
- **C**
- **PHP**

### Backend / Data
- MySQL（基本資料庫設計與操作）
- RESTful API 開發
- 雲端資料庫整合

### AI / Data
- Python 基礎資料處理
- PyTorch 基礎
- 感測器資料整理與分析

---

## 🚀 Projects

### 🌱 Smart Gardening Assistant（畢業專題）
**Technologies:** Python, IoT Sensors, API, Cloud Database, AI

- 整合土壤濕度與環境溫溼度感測器，即時監測植物狀態
- 根據感測數據自動控制澆水裝置
- 架設 API 串接雲端資料庫，自動收集與整理資料
- 透過 AI 模型分析不同植物需求，提供照護建議
- 結合天氣變化，優化澆水與管理策略

> 本專題讓我實際體驗從硬體、資料、後端到 AI 分析的完整流程。

🔗 **Live Website:** https://plantai-cac82.web.app  
🔗 **Project Repo:** https://github.com/你的帳號/smart-gardening-assistant

# 🏀 籃球公道伯｜NBA 2023–2024 例行賽數據分析（R / Flexdashboard）

「籃球公道伯」是一個以 **2023–2024 NBA 例行賽球員數據**為基礎的資料分析專案。  
因為平常很喜歡打籃球，我想把「看球的直覺」變成「用資料說話」，所以使用 **R 語言**抓取 Basketball-Reference 的公開資料，並以 **Flexdashboard** 做成可視化報告，透過各種圖表呈現球員表現與現代籃球趨勢（Three-Point Era）。

---

## 🎯 專案目標

- 以資料視覺化呈現 2023–2024 NBA 球員基本表現與分布
- 進一步探討進階指標（得分效率、控衛價值等）
- 分析「大三分時代」下，三分球對不同位置、效率指標的影響

---

## 📊 分析內容與圖表

### 1) 基礎分析（Basic Visualization）
- **得分王 Top 10（PTS）**：長條圖列出總得分前十名球員
- **得分文字雲（Top 100 Scorers）**：文字雲呈現前 100 名得分手，字體越大代表得分越高
- **年齡分布（Age Distribution）**：直方圖呈現球員年齡結構
- **位置分布（Position Distribution）**：圓餅圖顯示 PG/SG/SF/PF/C 人數比例

### 2) 進階分析（Advanced Metrics）
- **得分效率（MP vs PTS）**：散佈圖分析「上場時間（MP）」與「總得分（PTS）」的關係，用來觀察高效率得分手與刷分型球員
- **控衛價值（AST vs TOV）**：針對控球後衛（PG）用散佈圖分析助攻與失誤，尋找高助攻低失誤的優質控衛
- **180 俱樂部（50/40/90）**：篩選符合 FT% > 90%、FG% > 50%、3P% > 40% 的高效射手
- **買犯王（FTA per Game Top 10）**：長條圖列出場均罰球數最高的前十名球員，觀察造犯能力與進攻風格

### 3) 大三分時代（Three-Point Era）
- **出手佔比（3PA / FGA by Position）**：長條圖顯示各位置「三分出手佔總出手比例」，觀察長人是否也開始投三分
- **位置表現（3P% vs 3PA by Position）**：散佈圖比較各位置的三分命中率與出手次數
- **FG% vs eFG%（效率差異）**：比較傳統命中率與有效命中率，凸顯三分球對進攻效率的加成
- **三分球分佈（Interactive Scatter）**：互動式散佈圖呈現「三分進球數」與「命中率」的關係
- **空間型中鋒（3PA > 100）得分結構**：堆疊長條圖拆解中鋒得分來源（3PT / 2PT / FT 佔比），分析現代中鋒的技能變化

---

**Technologies:** R, Flexdashboard, rvest, ggplot2, wordcloud2, plotly

---

## 📦 資料來源
- Basketball-Reference：NBA 2023–2024 Totals  
  （本專案使用公開資料進行學術/個人分析用途）

---

## 🚀 如何執行（Run Locally）

### 1) 安裝 R 套件
在 RStudio 執行：

```r
install.packages(c(
  "rvest","dplyr","tidyr","ggplot2","wordcloud2",
  "plotly","flexdashboard","knitr","htmlwidgets","jsonlite","httr"
))

---

## 🤝 Team Experience

### 🏀 系籃隊隊長
- 負責隊伍訓練安排與成員溝通
- 在比賽壓力與突發狀況下做出即時決策
- 學習如何將成員放在最適合的位置，提升整體表現

### 🎉 系上活動支援 / 新生宿營隊輔
- 協助活動執行、拍攝與現場支援
- 與不同背景的人合作，提升溝通與應變能力

---

## 🌍 Language Skills

- **English**
  - TOEIC: 800
  - GEPT: 中級
  - 能閱讀英文技術文件，並進行基本商務溝通

---

## 💼 Experience

### 外場工讀生｜洪樓小館（台北市士林區）
**2023/07 – 2023/08**
- 協助現場營運與顧客服務
- 在高峰時段保持效率與穩定度
- 培養責任感與抗壓能力

---

## 🎯 Career Goal

希望能在後端工程、系統開發或 AI 相關實習中：
- 持續精進技術能力
- 從實務中學習系統思維
- 成為一位**穩定、可靠、能被信任的工程師**

