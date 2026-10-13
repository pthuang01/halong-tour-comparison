# 🌊 雙龍奇境‧碧波萬頃｜北越雙龍灣奢享五日行旅

本專案為「北越雙龍灣五日奢享行旅」專屬客製的高質感活動宣傳單頁網站（Single-Page Website）。採用現代法式殖民與東方山水融合之奢華視覺風格（Indochine Luxury Editorial Style），加入在地真實實景照片、飯店多圖數學級無縫斜切視覺、全螢幕圖片燈箱、互動式日程時間軸、美食與住宿規格導覽、以及匯率計算工具，專為提供極致閱讀體驗而打造

---

## ✨ 頁面特色亮點

1. **視覺設計（Artistic Luxury Aesthetics）**：
   - 結合翡翠綠（Indochine Emerald）與法式香檳金（Champagne Gold），展現下龍灣碧水與奢華遊輪氛圍
   - 採用優雅英文字體（Playfair Display / Cinzel）與古典中文襯線字體（思源宋體 Noto Serif TC），兼具精品雜誌感與舒適閱讀體驗
2. **飯店多圖無縫斜切展示（Unified Seamless Diagonal Split）**：
   - **河內格蘭美爵 / L7 西湖樂天**：雙圖完美無縫接合，單道金色漸層斜切細線精確分割
   - **下龍溫德姆傳奇 / DC遊艇 / 麗笙藍**：三圖完全並排拼接，斜切斜率與光暈效果 100% 統一平行，徹底消除黑底雜縫
3. **實景照片全螢幕燈箱（Lightbox Gallery）**：
   - 嚴選現場高解析實景照片（包含下龍灣海灣、太陽之眼摩天輪、女皇雙層纜車、先鋒號遊輪、驚訝洞億年鐘乳石、天井洞穿洞小舟、廣寧博物館、長安手搖舟、三谷碧洞古剎、河內百年聖約瑟夫大教堂、頂級龍蝦美饌等）
   - 點擊任一張照片即可開啟全螢幕高解析度燈箱檢視
   - 本地儲存圖片資源（位於 `images/`），上傳至 GitHub Pages 零依賴、不破圖、極速載入
4. **五日行程流暢互動（Interactive 5-Day Timeline）**：
   - 支援快速點擊 Day 1～Day 5 錨點平滑跳轉
   - 每日均清楚標示景點特色、當日精選餐飲（如 US$20 海陸百匯、US$55 頂級龍蝦饗宴、名店香焰雞火鍋、紅白酒暢飲）與星級住宿
5. **貼心旅行小錦囊**：
   - **越南盾 ⇄ 新台幣 即時匯率計算器**：出遊採買快速換算（參考匯率約 1 TWD ≈ 770 VND，實際以換匯當日匯率為準）
   - **氣候穿著與時差插座指南**：出發前一目了然

---

## 🚀 如何發布至 GitHub Pages（3 步驟快速上線）

你可以透過以下兩種方式將本網頁放上 GitHub Pages 免費託管：

### 方法 A：使用 Git 命令行（推薦）
在終端機（Terminal）或 PowerShell 中進入此資料夾，執行：

```bash
# 1. 初始化 Git 倉庫
git init

# 2. 加入所有檔案並提交
git add .
git commit -m "feat: 北越雙龍灣五日奢享行旅宣傳單頁"

# 3. 建立 main 分支
git branch -M main

# 4. 關聯你在 GitHub 上建立的儲存庫（請替換成你的 GitHub 帳號與 repo 名稱）
git remote add origin https://github.com/YOUR_USERNAME/vietnam-tour.git

# 5. 推送程式碼
git push -u origin main
```

### 方法 B：直接在 GitHub 網頁上傳
1. 登入 [GitHub](https://github.com/) 並點擊右上角 **New repository** 建立一個新倉庫（例如取名為 `vietnam-luxury-tour`）
2. 在新倉庫頁面點擊 **uploading an existing file**
3. 將本資料夾內的 `index.html`、`images/` 資料夾與 `.nojekyll` 拖曳上傳，點擊 **Commit changes**

---

### 🌐 啟用 GitHub Pages 設定
1. 進入你的 GitHub 儲存庫頁面，點擊上方的 **Settings**（設定）
2. 在左側選單點擊 **Pages**
3. 在 **Build and deployment** > **Branch** 下方：
   - 將分支選擇為 `main`
   - 資料夾選擇為 `/ (root)`
   - 點擊 **Save**
4. 等候約 1～2 分鐘，頁面上方即會出現你的專屬網址：
   > `https://YOUR_USERNAME.github.io/vietnam-luxury-tour/`
5. 將這個網址發布即可在手機或電腦上直接瀏覽

---

## 📂 檔案目錄結構

```text
├── index.html       # 完整的單頁宣傳網站主檔案（包含 HTML、Tailwind CSS、字體與 JS 互動）
├── images/          # 27 張現場景點與飯店高解析照片（本地完整託管）
├── .nojekyll        # 避免 GitHub Pages 過濾檔案之設定
└── README.md        # 專案說明與最新部署教學
```
