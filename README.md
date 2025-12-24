# 🎬 Video Last Frame Extractor

> 專為 AI 創作者設計的輕量化工具 — 一鍵提取影片最後一幀，完美保存您的 AI 生成作品

[![Made for AI Creators](https://img.shields.io/badge/Made%20for-AI%20Creators-blueviolet?style=flat-square)](https://github.com)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-brightgreen?style=flat-square)](https://github.com)
[![Privacy First](https://img.shields.io/badge/Privacy-100%25%20Local-blue?style=flat-square)](https://github.com)

---

## 📖 專案簡介

**Video Last Frame Extractor** 是一款專為 AI 影像創作者打造的瀏覽器端工具。當您使用 Runway、Pika、Sora 等 AI 影片生成工具時，經常需要提取影片的最後一幀作為下一段生成的起始圖像，或用於作品集展示。這款工具讓您無需安裝任何軟體，只需拖放影片即可獲得高品質 PNG 圖像。

### 🎯 為什麼需要這個工具？

在 AI 影片創作流程中，「最後一幀」扮演著關鍵角色：
- **無縫接續**：將最後一幀作為下一段 AI 影片的起始圖，實現連貫的長影片製作
- **品質保存**：以無損 PNG 格式保存，避免重複壓縮造成的畫質損失
- **效率提升**：告別繁瑣的影片編輯軟體，一鍵完成提取工作

---

## ✨ 功能特色

| 功能 | 說明 |
|------|------|
| 🖱️ **拖放上傳** | 直覺的拖放介面，支援點擊選擇檔案 |
| 🎥 **多格式支援** | 相容 MP4、WebM、MOV 等主流影片格式 |
| 🖼️ **無損輸出** | 以 PNG 格式輸出，保留原始解析度與色彩 |
| 🔒 **完全離線** | 所有處理在本地完成，影片不會上傳至任何伺服器 |
| 🌙 **深色模式** | 精心設計的深色介面，減輕長時間創作的視覺疲勞 |
| 📱 **響應式設計** | 支援桌面與行動裝置瀏覽器 |

---

## 🚀 使用方式

### 線上使用（推薦）

1. 訪問線上版本
2. 將影片拖放至上傳區域（或點擊選擇檔案）
3. 等待自動處理完成
4. 點擊「下載原始 PNG」保存圖像

### 本地使用

```bash
# 克隆專案
git clone https://github.com/YOUR_USERNAME/Video-lastframe-extractor.git

# 進入專案目錄
cd Video-lastframe-extractor

# 使用任意方式開啟 index.html
# 方式一：直接雙擊 index.html
# 方式二：使用本地伺服器
npx serve .
```

---

## 🛠️ 技術架構

- **純前端實作**：HTML5 + CSS3 + Vanilla JavaScript
- **樣式框架**：Tailwind CSS（CDN 引入）
- **核心技術**：Canvas API、Video API
- **零依賴**：無需 npm 安裝，開箱即用

---

## 🔮 未來展望

### Google Antigravity 整合計畫

本專案預留與 **Google Antigravity** 深度整合的擴充介面，未來版本將支援：

- 🤖 **AI 智能增強**：自動偵測影片關鍵幀，提供多幀選擇建議
- 🎨 **圖像優化建議**：分析提取的畫面，提供適合作為 AI 生成起始圖的修改建議
- 🔗 **工作流整合**：一鍵將提取的圖像作為 prompt 輸入至 AI 圖像生成服務
- ☁️ **雲端協作**：透過 Antigravity API 實現跨裝置的創作接續

> 💡 *此功能正在規劃中，敬請期待後續更新。*

---

## 📄 授權條款

本專案採用 [MIT License](LICENSE) 開源授權。

---

## 🙏 致謝

感謝所有 AI 創作者的回饋與建議，讓這個工具能夠持續改進。

---

<p align="center">
  <sub>Made with ❤️ for AI Creators</sub>
</p>
