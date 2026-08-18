# 🎮 AI 小遊戲作品集 (AI Mini-Games Portfolio)

> 本專案為 **AI 時代的專案管理師養成班** 精選成果作品集。集合了動作射擊、休閒養成、旅遊地圖導覽與數據分析等多款原創互動網頁小遊戲與工具應用。
> 全專案採用 **100% 純前端技術架構**，無須安裝任何後端環境，即開即玩！

---

## 🌟 作品列表 (Projects)

| 作品名稱 | 檔案名稱 | 類型分類 | 核心技術與特色 |
| :--- | :--- | :--- | :--- |
| **霧色獵殺：仿生軌跡**<br>`Mist Hunt: Bionic Trajectory` | [`mist_hunt_bionic_trajectory.html`](./mist_hunt_bionic_trajectory.html) | 動作射擊 / 街機生存 | 賽博龐克風格街機彈幕射擊遊戲。具備 CRT 復古掃描線濾鏡、仿生粒子物理軌跡、全屏 EMP 衝擊波絕招與 Web Audio API 電子合成音效。 |
| **全能喝水動力站**<br>`Hydration Quest` | [`HYDRATION QUEST.html`](./HYDRATION%20QUEST.html) | 休閒養成 / 健康生活 | 結合每日飲水目標與養成機制的趣味互動遊戲。具備真實流體水波動畫、等級成就解鎖、歷史數據統計圖表與過關彩帶慶祝特效。 |
| **台灣旅遊景點互動地圖**<br>`Taiwan Travel Explorer` | [`map.app.html`](./map.app.html) | 探索導覽 / 互動地圖 | 探索台灣在地美景的互動式地圖導覽工具。支援全台縣市即時分區篩選、地圖標記定位聯動、景點深度圖文導覽與行程探索。 |
| **ETF 歷年配息數據分析儀表板**<br>`ETF Yield Analytics Dashboard` | [`etf.html`](./etf.html) | 數據探索 / 財經分析 | 專業級 ETF 歷史配息與殖利率分析工具。支援本機 Excel 報表拖曳解析、複合表頭自動辨識、歷年配息趨勢圖表、高殖利率篩選排行榜與投資回測試算。 |

---

## ✨ 首頁平台亮點 (`index.html`)

- 🎨 **現代視覺美學 (Modern Glassmorphism)**：深色夜幕科技感設計，搭配賽博霓虹光暈與動態微粒網格背景。
- 🧊 **3D 卡片視差懸停 (3D Parallax Tilt)**：游標懸停於作品卡片時，卡片會自動隨滑鼠產生立體 3D 傾斜與光澤折射。
- 🚀 **即時試玩彈窗 (Modal Preview Runner)**：每款遊戲皆支援在首頁直接以內嵌彈窗快速試玩，無需跳轉離開頁面。
- 🔍 **即時搜尋與分類篩選 (Search & Filter)**：支援「全部作品」、「動作射擊」、「休閒養成」、「探索地圖」、「數據分析」一鍵切換，並具備即時關鍵字搜尋。
- 📱 **全平台 RWD 響應式佈局 (Responsive Design)**：完美適配手機（單欄手勢滑動）、平板與桌機大螢幕。

---

## 🛠️ 技術堆疊 (Tech Stack)

### 核心技術
- **HTML5**：語意化標籤結構、Canvas 2D 圖形渲染
- **CSS3**：Vanilla CSS、CSS Variables、Tailwind CSS、流體水波動畫、玻璃擬態濾鏡
- **JavaScript (ES6+)**：DOM 操作、事件監聽、非同步處理、Web Audio API

### 第三方開源函式庫
- **[ECharts 5.4](https://echarts.apache.org/)**：多維度互動數據視覺化圖表
- **[Chart.js](https://www.chartjs.org/)**：輕量級響應式圖表繪製
- **[Leaflet.js](https://leafletjs.com/)**：輕量級互動式地圖核心
- **[SheetJS (xlsx)](https://sheetjs.com/)**：本機端快速解析 Excel (.xlsx / .xls) 報表
- **[Canvas Confetti](https://www.kirilv.com/canvas-confetti/)**：成就解鎖與通關慶祝紙花特效
- **[FontAwesome 6](https://fontawesome.com/)** & **Google Fonts (`Inter`, `Noto Sans TC`, `Rajdhani`)**

---

## 📁 專案檔案結構 (File Structure)

```text
my_Artifact/
├── index.html                        # AI 小遊戲作品集首頁 (入口頁面)
├── mist_hunt_bionic_trajectory.html  # 霧色獵殺：仿生軌跡 (賽博龐克射擊遊戲)
├── HYDRATION QUEST.html              # 全能喝水動力站 (飲水養成小遊戲)
├── map.app.html                      # 台灣旅遊景點互動地圖 (旅遊探索地圖)
├── etf.html                          # ETF 歷年配息數據分析儀表板 (財經數據工具)
└── README.md                         # 專案說明文件
```

---

## 🚀 快速開始 (Quick Start)

本專案所有檔案皆為純前端架構，可透過以下任一方式開啟：

### 方法一：直接點擊開啟
使用檔案總管進入本專案資料夾，直接雙擊 `index.html` 即可使用預設瀏覽器（Chrome、Edge、Safari、Firefox）瀏覽。

### 方法二：透過 本地靜態伺服器 (推薦)
若希望獲得最佳快取與安全性體驗，可於專案目錄執行：

```bash
# 使用 Python 內建伺服器
python -m http.server 8080

# 或使用 Node.js http-server
npx http-server -p 8080
```
開啟瀏覽器前往 `http://localhost:8080/index.html` 即可暢玩。

---

## 📄 版權宣告 (License)

© 2026 **AI 時代的專案管理師養成班**. All Rights Reserved.
