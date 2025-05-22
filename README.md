# Vue Lottie UI Starter

一個整合了 Vue 3、Tailwind CSS 和 Lottie 動畫的現代化前端啟動模板。這個專案旨在幫助開發者快速搭建具有精美動畫效果的 Web 應用介面。

## ✨ 特性

- 🖼️ 整合 Lottie 動畫支援
- 🎨 使用 Tailwind CSS 進行樣式設計
- ⚡ Vite 建構工具，開發體驗極致
- 🔧 Vue 3 Composition API
- 📱 響應式設計

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

## 🎨 自定義

### 添加新的 Lottie 動畫

1. 在 [LottieFiles](https://lottiefiles.com/) 找到或上傳你的動畫
2. 複製動畫的 JSON URL 或下載 JSON 檔案
3. 在元件中使用 `lottie-player` 標籤：

```vue
<lottie-player
  src="你的動畫JSON路徑"
  background="transparent"
  speed="1"
  style="width: 300px; height: 300px"
  loop
  autoplay
/>
```

### 自定義樣式

專案使用 Tailwind CSS 進行樣式設計，你可以：

1. 直接在模板中使用 Tailwind 的工具類
2. 在 `tailwind.config.js` 中自定義主題
3. 在元件中使用 `<style>` 標籤添加自定義 CSS

## 📝 授權條款

[MIT](LICENSE)