# README

<div align="center">

# ✦ &nbsp; L · Y · Z &nbsp; ✦
### Personal Portfolio Website

<br>

**🌐 Live Demo**

[![Visit Website](https://img.shields.io/badge/🔗%20%20Visit%20Portfolio-lyz--0422.github.io-6b4c32?style=for-the-badge&labelColor=1c1814)](https://lyz-0422.github.io/test0305/)

<br>

[![index](https://img.shields.io/badge/首頁-index.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/index.html)&nbsp;
[![about](https://img.shields.io/badge/作品集-about.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/about.html)&nbsp;
[![notes](https://img.shields.io/badge/學習筆記-notes.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/notes.html)&nbsp;
[![exercise](https://img.shields.io/badge/練習題-exercise.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/exercise.html)&nbsp;
[![decide](https://img.shields.io/badge/今日決策-decide.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/decide.html)&nbsp;
[![weekend](https://img.shields.io/badge/週末去哪-weekend.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/weekend.html)

<br>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

<br>

> 電機工程系學生 · 深度學習研究者 · Android 開發者  
> 純靜態前端 · 零框架依賴 · 直接部署

</div>

---

## 目錄

- [專案簡介](#-專案簡介)
- [網頁結構](#-網頁結構)
- [功能特色](#-功能特色)
- [技術堆疊](#-技術堆疊)
- [專題一覽](#-專題一覽)
- [如何使用](#-如何使用)
- [自訂說明](#-自訂說明)
- [聯絡方式](#-聯絡方式)
- [授權說明](#-授權說明)

---

## 📖 專案簡介

這是 **LYZ**（呂尹筑）的個人作品集網站，以純 HTML / CSS / JavaScript 打造，**無框架依賴、零後端需求**，可直接靜態部署至 GitHub Pages。

網站涵蓋三大核心：個人學術背景與技術能力的展示、六個代表性課程專題的深度介紹，以及可互動操作的前端課程學習筆記。整體視覺以 **Warm Parchment（暖色調紙張質感）** 為主軸，融合現代排版美學與豐富的 CSS / JS 動畫效果。

```
🎓  學歷  逢甲大學通訊工程系 → 中原大學電機工程系
🤖  專長  深度學習 · PyTorch · Android · MATLAB · PCB 設計
🏆  成果  腦腫瘤 MRI 分類 F1-Score 97.54%（DenseNet121）
```

---

## 🗺 網頁結構

```
test0305/
│
├── index.html          ← 首頁 Landing Page
│   └── 磁性游標 / 粒子背景 Canvas / 打字機 / 3D 裝飾圓 / 跑馬燈
│
├── about.html          ← 作品集主頁（SPA 單頁架構）
│   ├── #hero           英雄區塊（個人卡片 + 統計數據）
│   ├── #about          學術背景介紹
│   ├── #skills         六張 3D 翻轉技能卡
│   ├── #projects       六個專題列表 → 各自詳情頁（JS 切換）
│   └── #contact        四種聯絡管道
│
├── notes.html          ← 課程學習筆記（互動式 Demo）
│   ├── Unit 01         JavaScript 基礎（JS·01 ~ JS·04）
│   ├── Unit 02         CSS Layout（CSS·01 ~ CSS·04）
│   └── Unit 03         非同步操作與 API 串接（ASYNC·01 ~ ASYNC·04）
│
├── exercise.html       ← 課後練習題（對應 Notes 各單元）
│   ├── JS · 01–04      型別偵測 · 陣列操作 · DOM · 計時器
│   ├── CSS · 01–04     FlexBox · Grid · RWD · Animation
│   └── ASYNC · 01–04   setTimeout · Promise · fetch · 綜合應用
│
├── decide.html         ← 今日決策中心（轉盤 + localStorage）
│   ├── 🍜 吃什麼       依人數 / 預算 / 用餐時間篩選
│   ├── 👗 穿什麼       依天氣 / 場合 / 個人風格篩選
│   └── 🎬 看什麼       依時間 / 心情 / 類型篩選
│
└── weekend.html        ← 週末去哪玩（景點推薦 + 轉盤 + 願望清單）
    ├── 條件設定         距離 / 預算 / 室內外 / 人數
    ├── 景點卡片         篩選後最多顯示 6 個推薦
    ├── 轉盤             隨機從推薦景點中選一個
    └── 願望清單         加入 + 管理（localStorage）
```

### `index.html` — 首頁

全螢幕固定高度 Landing Page，作為整個作品集的視覺入口。

| 元件 | 說明 |
|------|------|
| 磁性游標 | 點狀 + 環狀雙層游標，hover 元素時放大並改色 |
| 粒子背景 | Canvas 繪製 65 顆粒子，滑鼠靠近時粒子受吸引偏移，粒子間距內連線 |
| 字母進場 | 標題 `L · Y · Z` 逐字以 3D `rotateX(-45deg)` 翻轉進場 |
| 打字機 | 六個身份標籤循環顯示，帶有游標閃爍效果 |
| 3D 裝飾圓 | 三層同心圓 + `preserve-3d` 浮動旋轉，中心顯示計數動畫 |
| 跑馬燈 | 固定在底部的技術標籤無縫滾動列 |
| 液態按鈕 | hover 時圓形背景從底部液態上升 |

### `about.html` — 作品集主頁

採用 **SPA 單頁應用** 架構，同一頁面包含首頁（`#home-view`）、專題詳情（`#detail-view`）、技能詳情（`#skill-view`）三個 View，由 JavaScript 控制顯示切換，無需重新載入頁面。

| 區塊 | 主要內容 |
|------|---------|
| **01 — About** | 就讀學校、研究興趣、個人介紹 |
| **02 — Skills** | 六張翻轉卡：深度學習 · 程式開發 · 資料科學 · 應用部署 · 硬體實作 · 開發工具 |
| **03 — Projects** | 六個專題列表，點擊展開詳情頁，含完整技術說明、元件表、研究成果 |
| **04 — Contact** | Email · GitHub · Instagram · Threads |

### `notes.html` — 課程學習筆記

互動式學習筆記，點擊卡片展開，提供可操作的即時 Demo。

| 單元 | 篇號 | 主題 | Demo 功能 |
|------|------|------|-----------|
| Unit 01 | JS·01 | 變數、型別、函式 | 四則運算計算機 |
| Unit 01 | JS·02 | 陣列、物件、JSON | Push / Map 陣列操作面板 |
| Unit 01 | JS·03 | DOM 操作與事件 | 動態待辦事項列表 |
| Unit 01 | JS·04 | 計時器與動態效果 | 碼錶（Start / Pause / Reset） |
| Unit 02 | CSS·01 | FlexBox | `justify-content` 即時調整預覽 |
| Unit 02 | CSS·02 | Grid | `grid-template-columns` 即時切換 |
| Unit 02 | CSS·03 | RWD 響應式設計 | 手機 / 電腦版面切換模擬 |
| Unit 02 | CSS·04 | CSS Animation | Spin / Bounce / Pulse 動畫選擇器 |
| Unit 03 | ASYNC·01 | 同步與非同步 | Event Loop 執行順序視覺化 |
| Unit 03 | ASYNC·02 | Callback 與 Promise | Promise 鏈狀態即時追蹤 |
| Unit 03 | ASYNC·03 | fetch 與 async/await | 呼叫 JSONPlaceholder 公開 API |
| Unit 03 | ASYNC·04 | 多個請求與整合 | Promise.all 並行 vs 序列比較 |

### `exercise.html` — 課後練習題

對應 Notes 各單元的課後練習，點擊「▶ Execute」即時執行並顯示輸出，部分題目附有互動 UI 可直接操作。

### `decide.html` — 今日決策中心

三分類轉盤決策工具，依條件篩選後隨機抽選，結果可儲存至決策紀錄（`localStorage['decideHist']`，最多 12 筆）。

### `weekend.html` — 週末去哪玩

台灣景點推薦系統，依距離 / 預算 / 室內外 / 人數篩選，轉盤隨機選擇，可加入願望清單（`localStorage['weekendWishlist']`，最多 9 筆）。

---

## ✨ 功能特色

### 🎨 視覺設計

- **Warm Parchment 色系**：統一暖色調紙張質感，配色柔和不刺眼
- **噪點紋理**：以 SVG `feTurbulence` fractalNoise 疊加全頁輕微噪點，強化紙質感
- **三字型系統**：Playfair Display（標題）、DM Mono（數據/標籤）、Noto Sans TC（中文正文）
- **mix-blend-mode**：游標點以 `multiply` 混合模式與背景融合

### 🎬 動畫系統

- **進場動畫**：`charIn`（字母 3D 翻轉）、`slideUp`（向上滑入）、`navIn`（導覽列下滑）
- **Scroll 觸發**：`IntersectionObserver` 監聽 `.reveal` 元素，滾動進入視窗才播放動畫
- **Hover 特效**：按鈕液態填充、專題行左側指示條 `scaleY`、技能卡 `rotateY(180deg)` 3D 翻轉
- **持續動畫**：Canvas 粒子系統、3D 浮動裝飾圓、跑馬燈無縫循環、磁性游標跟隨

### 📱 響應式設計

| 斷點 | 佈局行為 |
|------|---------|
| `> 1024px` | 雙欄 Grid（英雄區 / About 區）、技能卡三欄 |
| `≤ 1024px` | 單欄堆疊、技能卡二欄 |
| `≤ 640px` | 全單欄、漢堡選單展開、技能卡停用 3D 翻轉（避免觸控衝突） |

### 🧩 SPA 深度連結

`about.html` 支援 URL 查詢參數，瀏覽器直接帶 `?project=` 或 `?skill=` 即可跳至對應詳情頁：

```
about.html?project=ai      → 腦腫瘤 MRI 影像分類系統
about.html?skill=dl        → 深度學習技能詳情
```

---

## 🛠 技術堆疊

### 核心語言

| 技術 | 主要用途 |
|------|---------|
| **HTML5** | 語意化標籤、Canvas API、`data-*` 屬性 |
| **CSS3** | Custom Properties · Flexbox · Grid · `@keyframes` · `backdrop-filter` · `perspective` |
| **JavaScript ES6+** | `IntersectionObserver` · `requestAnimationFrame` · `URLSearchParams` · Canvas 2D · `fetch` / `async-await` |
| **localStorage** | 決策紀錄與景點願望清單的輕量本地儲存 |

### 字型（Google Fonts）

| 字型 | 用途 |
|------|------|
| `Playfair Display` | 大標題、章節標題、裝飾數字 |
| `DM Mono` | 標籤、數據、程式碼風格文字 |
| `Noto Sans TC` | 中文正文、說明段落 |

### 設計色彩變數

```css
:root {
  --bg:  #faf7f2;             /* 暖白底色       */
  --bg2: #f4efe6;             /* 次要底色       */
  --sf:  #ede7db;             /* 表面色         */
  --bd:  #d8cfc2;             /* 邊框色         */
  --bd2: #c9bfb0;             /* 次要邊框       */
  --tp:  #1c1814;             /* 主文字色       */
  --ts:  #5c5147;             /* 次要文字       */
  --tm:  #9c9080;             /* 輔助文字       */
  --ac:  #6b4c32;             /* 主色（咖啡棕） */
  --ac2: #7d5a3c;             /* 主色 hover     */
  --as:  rgba(107,76,50,.09); /* 主色透明背景   */
}
```

### 無外部依賴

本專案完全不依賴任何第三方 JavaScript 套件或 CSS 框架（jQuery、Bootstrap、React 等），所有互動效果、動畫、版面均以 **原生 Web API** 實作。

---

## 🗂 專題一覽

| # | 專題名稱 | 課程 / 學年 | 主要技術 |
|---|---------|------------|---------|
| 01 | 藍芽遙控自走車 | 逢甲通訊系 · 大一專題 | `Arduino` `HC-05` `L298N` `App Inventor` |
| 02 | 卷積的三種實現方式 | 逢甲通訊系 · 數位信號處理 | `MATLAB` `FFT` `線性卷積` `循環卷積` |
| 03 | Android 程式設計 Final | 逢甲通訊系 · Android 程式設計 | `Android Studio` `Java` `ListView` `GridView` |
| 04 | PCB 電路板製作 | 逢甲 · 電子學 | `PCB蝕刻` `曝光顯影` `焊接` `示波器` |
| 05 | 聲控 LED 旋律套件 | 逢甲 · 電子學 | `EAGLE` `BJT放大器` `PCB Layout` `焊接` |
| 06 | 腦腫瘤 MRI 影像分類系統 | 逢甲通訊系 · 大四畢業專題 | `PyTorch` `DenseNet121` `Streamlit` `CUDA` |

<details>
<summary><b>🏆 畢業專題詳情：腦腫瘤 MRI 影像分類系統</b></summary>

<br>

**研究目的**  
比較三種深度學習模型在四類腦腫瘤 MRI 影像分類的最佳表現，並部署至 Streamlit 網頁平台輔助醫學生判讀。

**資料集**  
Kaggle Brain Tumor MRI Dataset — 4 類 × 1,605 張，共 **6,420 張** MRI 影像，resize 至 224×224，搭配隨機水平翻轉資料擴增。

**實驗設定**

| 參數 | 設定值 |
|------|--------|
| 交叉驗證 | 3-Fold Cross Validation |
| 學習率 | 0.00005 |
| 批次大小 | 32 |
| 優化器 | Adam |
| 損失函數 | Cross Entropy Loss |
| 早停法 | ✓ |

**模型比較結果**

| 模型 | 平均 F1-Score |
|------|--------------|
| ★ **DenseNet121** | **97.54%** |
| EfficientNetB0 | 96.98% |
| ResNet50 | 96.42% |

**DenseNet121 指標（最終模型）**

| Accuracy | Precision | Recall | F1-Score |
|----------|-----------|--------|----------|
| 97.54% | 97.56% | 97.54% | 97.54% |

**硬體環境**  
`Windows 11` · `Intel i7-13620H` · `RTX 4060` · `32GB RAM` · `CUDA 12.1` · `Python 3.8`

</details>

---

## 🚀 如何使用

### 線上瀏覽（推薦）

直接點擊連結，無需任何安裝：

| 頁面 | 網址 |
|------|------|
| 🏠 首頁 | https://lyz-0422.github.io/test0305/index.html |
| 📁 作品集 | https://lyz-0422.github.io/test0305/about.html |
| 📝 學習筆記 | https://lyz-0422.github.io/test0305/notes.html |
| 🧪 課後練習 | https://lyz-0422.github.io/test0305/exercise.html |
| 🎯 今日決策 | https://lyz-0422.github.io/test0305/decide.html |
| 🗺 週末去哪 | https://lyz-0422.github.io/test0305/weekend.html |

### 本地執行

```bash
# Step 1：Clone 此儲存庫
git clone https://github.com/lyz-0422/test0305.git

# Step 2：進入目錄
cd test0305
```

選擇以下任一方式啟動本地伺服器：

```bash
# ── 方法 A：Python（推薦，通常已內建）──
python -m http.server 8080
# 瀏覽器開啟 → http://localhost:8080

# ── 方法 B：Node.js ──
npx serve .
# 瀏覽器開啟 → http://localhost:3000

# ── 方法 C：VS Code ──
# 安裝 Live Server 擴充 → index.html 右鍵 → Open with Live Server
```

> **注意**：建議使用本地伺服器而非直接以 `file://` 開啟，以確保字型載入、粒子動畫等效果完整運作。

---

## 🎨 自訂說明

### 1. 個人資訊

搜尋並替換 `about.html` 中的以下文字：

```html
<!-- 英雄區塊介紹 -->
<p class="hero-p">電機工程系學生 · 深度學習研究者。...</p>

<!-- About 段落 -->
<p class="about-p">我目前就讀於 <span class="hl">中原大學電機工程學系</span>...</p>

<!-- 統計數字 -->
<div class="stat-num">6</div>     <!-- 專題數量 -->
<div class="stat-num">97%+</div>  <!-- 代表成果 -->
```

### 2. 打字機文字

修改 `index.html` 中的身份標籤陣列：

```javascript
const phrases = [
  "深度學習研究者",
  "電機工程系學生",
  "Android App Developer",
  // 替換成您自己的身份標籤 ...
];
```

### 3. 新增專題

在 `about.html` 的 `PROJECTS` 物件中加入新條目：

```javascript
myproject: {
  num:      "Project 07 · 課程名稱",
  title:    ["專題標題第一行", "第二行（斜體）"],
  sub:      "一行簡短說明。",
  tags:     ["技術標籤1", "技術標籤2"],
  meta:     [{ label: "學校 / 課程", val: "XXX 大學 · 課程名稱" }],
  sections: [{ h: "章節標題", p: "段落內容。" }],
  sidebar:  [{ title: "側邊卡片", rows: [["Key", "Value"]] }]
}
```

並在 `.proj-list` 區塊加入對應按鈕：

```html
<button class="proj-row reveal" onclick="showDetail('myproject')">
  <span class="proj-n">07</span>
  <div>
    <div class="proj-year">大X · 課程名稱</div>
    <div class="proj-title">專題標題</div>
    <div class="proj-desc">一行簡短說明</div>
  </div>
  <div class="proj-tags"><span class="proj-tag">標籤</span></div>
  <span class="proj-arrow">↗</span>
</button>
```

### 4. 更換主色調

僅需修改三支檔案的 `:root` 中兩個變數，即可全站換色：

```css
:root {
  --ac:  #6b4c32;  /* 主色，改此即可 */
  --ac2: #7d5a3c;  /* hover 主色     */
}
```

### 5. 聯絡方式

修改 `about.html` 中的聯絡連結：

```html
<a class="contact-link reveal" href="mailto:your@email.com">...</a>
<a class="contact-link reveal" href="https://github.com/yourusername">...</a>
```

---

## 📬 聯絡方式

<div align="center">

| 平台 | 帳號 / 連結 |
|------|------------|
| 📧 Email | [lyz0422work@gmail.com](mailto:zoe920422@gmail.com) |
| 🐙 GitHub | [@lyz-0422](https://github.com/lyz-0422) |
| 📸 Instagram | [@lyzzz_0422](https://www.instagram.com/lyzzz_0422/) |
| 🧵 Threads | [@lyzzz_0422](https://www.threads.com/@lyzzz_0422) |

</div>

---

## 📄 授權說明

- ✅ 可改作自己的作品集
- ✅ 可學習程式碼結構與動畫實作方式
- ❌ 請勿直接複製個人簡介、學術資歷、專題內容等個人資料
- ❌ 請勿冒充作者身份對外展示

---

<div align="center">

<br>

**✦ &nbsp; Designed & Built by LYZ &nbsp; ✦**

<sub>逢甲大學通訊工程學系 → 中原大學電機工程學系 &nbsp;·&nbsp; 2026</sub>

<br>

[![GitHub](https://img.shields.io/badge/GitHub-lyz--0422-1c1814?style=flat-square&logo=github)](https://github.com/lyz-0422)

</div>