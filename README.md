# Vue Lottie UI Starter

## 🌟 專案緣起

在現代網頁開發中，動畫效果已經成為提升用戶體驗的關鍵元素。然而，製作高質量的網頁動畫往往需要深厚的設計功底和複雜的技術實現。這個專案誕生的初衷，就是為了解決這個痛點 —— 讓每個開發者都能輕鬆地在他們的 Web 應用中實現專業級的動畫效果。

我們選擇 Lottie 作為核心動畫解決方案，是因為它完美地平衡了設計自由度和開發便利性：

- 🎯 設計師可以在 After Effects 中自由創作，無需考慮技術限制
- 💻 開發者可以通過簡單的 JSON 文件整合動畫，無需深入動畫邏輯
- 🚀 最終用戶能享受到流暢的向量動畫，無需承擔沉重的加載負擔

## 🎯 專案目標

這個啟動模板旨在提供一個完整的 Vue 3 + Lottie 開發環境，幫助開發者：

- 快速搭建具有精美動畫效果的現代化 Web 應用
- 學習 Lottie 動畫整合的最佳實踐
- 探索 Vue 3 與 Tailwind CSS 的強大組合

## ✨ 特性

- 🖼️ 整合 Lottie 動畫支援
  - 內建 @lottiefiles/lottie-player
  - 支援 JSON 格式動畫文件
  - 提供動畫控制 API
- 🎨 使用 Tailwind CSS 進行樣式設計
  - 實用優先的 CSS 框架
  - 豐富的預設樣式
  - 高度可定制的設計系統
- ⚡ Vite 建構工具，開發體驗極致
  - 快速的熱更新
  - 優化的建構流程
  - 現代化的開發體驗
- 🔧 Vue 3 Composition API
  - 更好的代碼組織
  - 更強的類型推導
  - 更靈活的組件邏輯
- 📱 響應式設計
  - 移動優先的設計理念
  - 完整的斷點支援
  - 流暢的跨設備體驗

## 🚀 快速開始

### 前置要求

- Node.js 16.0 或更高版本
- npm 或 yarn 套件管理器

### 安裝步驟

1. 克隆專案
```bash
git clone <your-repository-url>
cd vue-lottie-ui-starter
```

2. 安裝依賴
```bash
npm install
# 或
yarn install
```

3. 啟動開發伺服器
```bash
npm run dev
# 或
yarn dev
```

4. 開啟瀏覽器訪問 http://localhost:5173

## 📦 建構

```bash
npm run build
# 或
yarn build
```

## 🛠️ 技術棧

- [Vue 3](https://v3.vuejs.org/) - 漸進式 JavaScript 框架
- [Vite](https://vitejs.dev/) - 下一代前端建構工具
- [Tailwind CSS](https://tailwindcss.com/) - 實用優先的 CSS 框架
- [Lottie](https://airbnb.design/lottie/) - 輕量級動畫庫

## 🎨 最佳實踐

### Lottie 動畫整合建議

1. **動畫資源優化**
   - 使用向量格式確保清晰度
   - 最小化 JSON 文件大小
   - 善用動畫預加載

2. **效能考量**
   - 適時使用動畫懶加載
   - 控制同時播放的動畫數量
   - 在適當時機銷毀動畫實例

3. **開發技巧**
   - 善用 LottieFiles 平台的免費資源
   - 使用動畫控制 API 實現互動效果
   - 結合 Vue 3 的生命週期管理動畫

## 📝 授權條款

[MIT](LICENSE)