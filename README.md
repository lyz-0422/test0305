<div align="center">

# ✦ &nbsp; L · Y · Z &nbsp; ✦
### Full-Stack Portfolio & Cloud Arcade Hub (2026)

<br>

**🌐 Live Demo**

[![Visit Website](https://img.shields.io/badge/🔗%20%20Visit%20Portfolio-lyz--0422.github.io-6b4c32?style=for-the-badge&labelColor=1c1814)](https://lyz-0422.github.io/test0305/)

<br>

[![index](https://img.shields.io/badge/大廳首頁-index.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/index.html)&nbsp;
[![about](https://img.shields.io/badge/個人作品集-about.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/about.html)&nbsp;
[![notes](https://img.shields.io/badge/全棧筆記-notes.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/notes.html)&nbsp;
[![exercise](https://img.shields.io/badge/技術沙盒-exercise.html-c9bfb0?style=flat-square)](https://lyz-0422.github.io/test0305/exercise.html)&nbsp;
[![login](https://img.shields.io/badge/雲端登入-login.html-ac?style=flat-square)](https://lyz-0422.github.io/test0305/login.html)&nbsp;
[![gamehub](https://img.shields.io/badge/數據大廳-gamehub.html-gold?style=flat-square)](https://lyz-0422.github.io/test0305/gamehub.html)

<br>

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Vue3](https://img.shields.io/badge/Vue%203-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white)](https://vuejs.org/)
[![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)](https://firebase.google.com/)

<br>

> 電機工程系學生 · 深度學習研究者 · Android 開發者  
> 整合雲端 BaaS 身分驗證 · 5 大高階原生街機遊戲系統 · Vercel 自動化自動部署

</div>

---

## 📋 目錄

- [專案簡介](#-專案簡介)
- [技術堆疊與全站架構亮點](#️-技術堆疊與全站架構亮點)
- [11 大網頁結構與底層架構解析](#-11-大網頁結構與底層架構解析)
- [🎮 數據大廳與 5 大核心街機解密](#-數據大廳與-5-大核心街機解密)
- [🗂 課程與畢業專題一覽](#-課程與畢業專題一覽)
- [🚀 如何使用與憑證](#-如何使用與憑證)
- [📬 聯絡方式](#-聯絡方式)
- [📄 授權說明](#-授權說明)

---

## 📖 專案簡介

這是 **LYZ**（呂尹筑）的個人全棧作品集與高階街機遊戲大廳。本專案將**電機/通訊工程硬體實作經驗**與**現代網頁全棧開發（Vue 3 生態圈 + Firebase 雲端服務）**進行深度整合。

網站不僅包含結構清晰的 SPA 作品展示牆與技術沙盒，更建構了一個完整的**雲端身分驗證門戶**。通過安全性守衛攔截，解鎖內置的 5 款完全由底層原生 JavaScript、HTML5 Canvas 及 Web Audio API 驅動的高性能復古街機遊戲，並具備全數據分析看板與戰績圖卡自動生成引擎。

🎓 學歷： 逢甲大學通訊工程系 → 中原大學電機工程系  
🤖 專長： 深度學習 · PyTorch · Firebase · Vue 3 · Android · PCB 設計  
🏆 成果： 腦腫瘤 MRI 分類 F1-Score 97.54% (DenseNet121) / 綜合 APM 戰力指標解鎖

---

## 🛠️ 技術堆疊與全站架構亮點

* **雲端身分驗證守衛 (BaaS Identity Guard)**：整合 Firebase Authentication 雲端安全憑證，在純前端環境實作非同步全域安全路由守衛，嚴格分流攔截非法入侵，保障刷榜環境安全性。
* **多源數據即時動態聚合演算法 (Data Aggregation)**：大廳能動態跨模組解析高達 20+ 組結構各異的 `localStorage` 排行榜與難度 JSON 字典，加算輸出綜合戰力極限（APM-X Index）。
* **純原生數位音訊合成器 (Synth Audio Engine)**：全站遊戲**零外部音訊檔案依賴**，純粹利用 HTML5 `AudioContext` 建立音訊振盪器（`OscillatorNode`），在運行期即時生成 8-bit 復古街機電子音效。
* **自製圖卡生成引擎 (Scorecard Generator)**：不依賴任何第三方圖像庫，純手寫 HTML5 Canvas 2D 矩陣調用繪圖上下文，具備雙重主題色彩配置矩陣，一鍵渲染出高畫質戰績圖卡下載。
* **全域主題同步與防閃爍 (Theme Sync & Anti-FOUC)**：利用立即執行函式 (IIFE) 阻斷深色模式載入前的畫面白光閃爍；實作 `window.storage` 監聽器，達成多視窗分頁主題瞬間即時同步。

---

## 🗺 11 大網頁結構與底層架構解析

```
test0305/
│
├── index.html          ← 個人首頁入口導覽大廳
├── about.html          ← 作品集與專案詳情頁（SPA 多重檢視架構）
├── notes.html          ← 網頁全棧架構技術筆記（高階滾動目錄監聽）
├── exercise.html       ← 課後實作沙盒主控台（封閉式互動 UI Console）
├── login.html          ← 雲端身分驗證安全門戶（Firebase Auth 連線）
├── gamehub.html        ← 雲端街機數據大廳（中央調度與戰力聚合中心）
│
├── game.html           ← 街機 01：誰是 DAVID 蛇 🐍（雙人對戰/蟲洞傳送/極限模式）
├── game2.html          ← 街機 02：Breakout 磚塊爆破 🧱（多球殘影/雙向道具機制）
├── game3.html          ← 街機 03：2048 數字矩陣 🔢（旋轉通解算法/歷史趨勢圖/無限 Undo）
├── game4.html          ← 街機 04：Memory Card 翻牌記憶 🃏（3D 翻轉/高壓倒數/Combo 加乘）
└── game5.html          ← 街機 05：Typing Speed 打字速度 ⌨️（NPC 競速/手殘紅色鍵盤熱圖）
```

### `index.html` — 個人首頁入口導覽大廳
* **非同步數據連動**：利用 `fetch()` 異步讀取 `about.html` 源碼，透過 `DOMParser` 即時檢索解析專案卡片數量，搭配動態三階貝氏曲線數字增加動畫（CountUp）渲染於 3D 浮動裝飾球中。
* **動態 Canvas 網格**：Canvas 繪製粒子星網，滑鼠靠近時粒子受磁性引力偏移，並在間距小於 180 像素時觸發流暢的動態連線特效。

### `about.html` — 個人簡介與專案詳情頁
* **SPA 視圖調度器**：同一頁面包含首頁（`#home-view`）、專題詳情（`#detail-view`）、技能詳情（`#skill-view`）三個 View，由 JavaScript 控制顯示切換，無需重新載入頁面。支援 URL 查詢參數（`?project=ai`）達成深度連結分流。
* **指標視覺化進度條**：在觸發專案注入後，利用定時器延遲動態將資料集屬性 `dataset.pct` 賦予給 CSS 的 `width` 屬性，觸發流暢的 CSS `transition` 硬體加速動畫。

### `notes.html` — 網頁全棧架構技術筆記
* **高階滾動監聽目錄 (Scroll-Linked TOC)**：利用原生 `Intersection Observer` 監聽筆記中 14 個單元的標頭元素，當使用者滾動筆記時，以 40% 的可視閾值精準捕獲當前區段，即時動態點亮左側 TOC 目錄。
* **全棧技術範疇**：完整收錄 JavaScript 基礎、CSS Layout、非同步 Promise、Vue 3 Ecosystem (Composition API, Composables, Setup Store)、Firebase Firestore CRUD 即時監聽與 Vercel 自動化自動部署（CI/CD）環境變數防護安全策略。

### `exercise.html` — 課後實作沙盒主控台
* **全封閉式網頁虛擬主控台**：客製化黑客風格的輸出容器，利用 JS 結合自訂的語意化狀態類別（`.log-ok`, `.log-wa`, `.log-er`），將沙盒代碼的運算結果與 Bug 分析直觀呈現。
* **計時器緒安全防護**：實作了嚴格的計時器指針防範機制（`if(exClockIv) return`），徹底杜絕重複點擊按鈕時，背景 `setInterval` 疊加產生的記憶體洩漏與執行緒卡死 Bug。

### `login.html` — 雲端身分驗證安全門戶
* **Firebase Auth 連線驗證**：引進 Firebase Web SDK，實作 `signInWithEmailAndPassword` 非同步驗證。直接連線 Google 雲端身分資料庫，達成符合業界標準的密碼加密雜湊與安全比對。
* **防禦鎖定狀態機**：點擊登入後立即鎖定按鈕（`disabled = true`）並變更文字，防止使用者因重複點擊發送多路多重請求。

---

## 🎮 數據大廳與 5 大核心街機解密

### 數據調度中心 (`gamehub.html`)
大廳實作安全路由攔截守衛，判定未登入者過導向登入頁。右上角貼心並排 **🚪 LOGOUT** 登出按鈕與主題快切鍵。中央綜合看板具備 **Gamer Rank 稱號動態計算** 與 **純 Canvas 2D 雙重主題色彩配置卡片生成器**，是一體化街機系統的控制核心。

### 01. 誰是 DAVID 蛇 🐍 (`game.html`)
* **雙線程獨立步長控制器**：在同一個 `requestAnimationFrame` 主迴圈中，根據玩家的加速狀態（`boosted`），為 P1（WASD 鍵）與 P2（方向鍵）計算獨立的更新時間步長。支援行動端**虛擬四向按鍵 D-Pad 觸控優化**。
* **蟲洞傳送與極限模式**：實作二維座標加算公式，當蛇頭進入 A 蟲洞會自動捕獲，並從 B 蟲洞的相對切線方向傳出。16 顆星星全部吃完後解鎖隱藏極限模式，5 秒後全程強行鎖定在極速衝刺狀態。

### 02. Breakout 磚塊爆破 🧱 (`game2.html`)
* **多球與軌跡淡入殘影**：球體物件內部維護一個上限為 6 幀的歷史座標佇列，利用 `shift()` 與 `push()` 持續汰換更新，並在 Canvas 上以 `rgba` 指數級遞減透明度繪製出流暢的彗星尾跡特效。
* **複合式隨機道具**：打碎特定方塊會掉落 `[W]`（擋板加寬 1.5 倍狀態鎖）與 `[M]`（多球分身，瞬間向外爆發分裂出 2 顆全新的實體球，獨立享有碰撞解算）。

### 03. 2048 數字矩陣 🔢 (`game3.html`)
* **通用矩陣旋轉解算器**：無論玩家往哪個方向滑動，JS 會先將當前二維陣列旋轉至統一的「標準左滑格式」，執行降維堆疊與相鄰元素合併後原路旋轉回對應方向。此演算法能**完全適應 4×4 經典版與 5×5 擴展版**。
* **歷史狀態回溯快照鏈**：實作無限步「悔棋（Undo）」功能。在發送位移前進行深拷貝快照備份，點擊悔棋時一鍵還原，並調用 `syncTilesDataWithGrid()` 徹底排除傳統方塊重疊與視覺錯位的 Bug。

### 04. Memory Card 翻牌記憶 🃏 (`game4.html`)
* **異步指針狀態鎖**：每次翻開第二張牌時，立即將全域 `locked` 設定為 `true`，切斷所有卡片的點擊事件。若判定配對失敗，定時器延遲 850 毫秒保持曝光，隨後移除翻牌狀態並重新釋放。
* **Combo 加乘系統**：實作動態多重加分鏈，分數依據 Score += 100 + (Combo × 50) 按階梯式劇烈暴增。搭配本機排名的數據裁剪，實作單機排行榜大名留榜功能。

### 05. Typing Speed 打字速度 ⌨️ (`game5.html`)
* **多人 AI 動態競速賽道**：內建即時擬真賽道系統。遊戲啟動時，系統會動態宣告兩組具有不同權重速度的虛擬 NPC 對手，隨時間推移使用微積分公式計算並同步推進對手頭像（User 蛇 🐍 / NPC 狐 🦊、獅 🦁）。
* **字母手殘打錯機率熱圖**：系統會將打錯的字元映射至 26 鍵矩陣字典（`errorKeyMap`）。測試結束後，會自動計算最大出錯權重值，在前端渲染出高質感的**紅色熱圖虛擬鍵盤 (Heatmap Keyboard)**。

---

## 🗂 課程與畢業專題一覽

| # | 專題名稱 | 課程 / 學年 | 主要技術與亮點表現 |
|---|---------|------------|---------|
| 01 | 藍芽遙控自走車 | 逢甲通訊系 · 大一專題 | `Arduino` `HC-05 藍芽` `L298N` `App Inventor` 軟硬體整合 |
| 02 | 卷積的三種實現方式 | 逢甲通訊系 · 數位信號處理 | `MATLAB` `FFT` 線性、循環、頻域卷積演算法等效性驗證 |
| 03 | Android 程式設計 Final | 逢甲通訊系 · Android 程式設計 | `Android Studio` `Java` `ListView` 追星主題 App 架構建構 |
| 04 | PCB 電路板製作 | 逢甲 · 電子學專題 | 手工曝光顯影、蝕刻、鑽孔全流程，示波器失效根因分析除錯 |
| 05 | 聲控 LED 旋律套件 | 逢甲 · 電子學小專題 | `EAGLE` 佈線、BJT 串級放大電路分析、手工精密焊接演練 |
| 06 | 腦腫瘤 MRI 影像分類系統 | 逢甲通訊系 · 大四畢業專題 | `PyTorch` `DenseNet121` `Streamlit` **模型最高 F1 達 97.54%** |

<details>
<summary><b>🏆 畢業專題詳情：腦腫瘤 MRI 影像分類系統 (點擊展開)</b></summary>

<br>

**研究目的** 比較三種高階卷積神經網路模型在四類腦腫瘤 MRI 影像分類上的最佳化表現，並建構醫學生輔助學習推論平台。

**資料集與預處理** 採用 Kaggle 大數據 Brain Tumor MRI Dataset — 共計 **6,420 張** 高解析度 MRI 影像，影像統一 Resize 至 224×224，並套用隨機水平翻轉進行資料增強。

**模型比較與關鍵成果** 系統性導入 **3 折交叉驗證 (3-Fold Cross Validation)** 搭配早停法（Early Stopping）防止過擬合：
* ★ **DenseNet121**：**平均 F1-Score 達到 97.54% 的極致精準度 (獲選為最終部署核心)**。
* EfficientNetB0：平均 F1-Score 為 96.98%。
* ResNet50：平均 F1-Score 為 96.42%。

**實驗環境硬體配置** `Windows 11` · `Intel i7-13620H` · `RTX 4060 GPU` · `32GB RAM` · `CUDA 12.1` · `Python 3.8`

</details>

---

## 🚀 如何使用與憑證

### 本地開啟沙盒環境

```bash
# Step 1：Clone 此儲存庫
git clone https://github.com/lyz-0422/test0305.git

# Step 2：進入目錄
cd test0305
```

選擇以下任一方式啟動本地伺服器以確保異步 Fetch 與 Firebase SDK 的權杖載入完整：

```bash
# 使用 Python 啟動本地埠口
python -m http.server 8080
# 瀏覽器開啟 → http://localhost:8080
```

> 🔐 **全站通用 Demo 測試登入帳密**
> * **測試 Email / 帳號**：`test@example.com`
> * **測試 Password / 密碼**：`123456`

---

## 📬 聯絡方式

<div align="center">

| 平台 | 帳號 / 連結 |
| --- | --- |
| 📧 Email | [zoe920422@gmail.com](mailto:zoe920422@gmail.com) |
| 🐙 GitHub | [@lyz-0422](https://github.com/lyz-0422) |
| 📸 Instagram | [@lyzzz_0422](https://www.instagram.com/lyzzz_0422/) |
| 🧵 Threads | [@lyzzz_0422](https://www.threads.com/@lyzzz_0422) |

**✦ Designed & Built by LYZ ✦**  
<sub>逢甲大學通訊工程學系 → 中原大學電機工程學系 · 2026</sub>

</div>

---

## 📄 授權說明

* ✅ 可改作自己的作品集
* ✅ 可學習程式碼結構與動畫實作方式
* ❌ 請勿直接複製個人簡介、學術資歷、專題內容等個人資料
* ❌ 請勿冒充作者身份對外展示