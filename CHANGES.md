# 項目修改記錄

## 2026-07-01 會話記錄

### 一、SEO 優化（index.html）
- 修復 title 錯字：`Homepag` → `Dekun Yuan | Ph.D. Student in Oceanography & Space Informatics`
- 新增 `meta description`、`meta keywords`、`meta author`
- 新增 Open Graph 標籤（og:title、og:description、og:type）

### 二、HTML 質量修復（index.html）
- 所有圖片補充 `alt` 屬性（個人照、論文縮圖）
- 用 `id` 取代廢棄的 `<a name>` 錨點，導航欄 href 同步更新
- 修復錯字：`Hobors` → `Honors`，`Sapce` → `Space`（兩處）
- 將 `Ph.D. Student` 更新為 `Ph.D. Candidate`（側邊欄及 About Me）

### 三、移動端適配（index.css）
- 螢幕寬度 ≤768px：側邊欄從 fixed 改為頂部單欄顯示
- 導航欄支持橫向滑動
- 論文縮圖在手機端自適應寬度

### 四、個人照片
- 替換圖片：`myself1.jpg` → `myself2.png`
- 移除圓形裁剪（`border-radius: 50%`）
- 圖片尺寸改為 `width: 210px; height: auto`（保持原始比例，居中顯示）

### 五、Favicon
- 舊：`favicon.ico`
- 新：`myself2.png`（同時設置 `shortcut icon` 和 `rel="icon" type="image/png"`）

### 六、Publications 鏈接顏色
- 有真實 URL 的鏈接顯示藍色（`#1a73e8`）
- 佔位 `href="#"` 的鏈接顯示灰色
- 修復 ZMIS-SAM Github 鏈接格式錯誤：`# https://...` → `https://...`
- 修復 ZS2Net Github 鏈接格式錯誤：`#https://...` → `https://...`
- 新增 ZS2Net `[Page]` 鏈接（ScienceDirect）

### 七、GitHub 部署
- 初始化 git 倉庫（`git init`）
- 遠端倉庫：`https://github.com/sdydk/sdydk.github.io.git`
- 分支：`master`
- 共推送 6 次提交（含一次 force push 覆蓋原遠端內容）
