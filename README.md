# 智能配電箱應用

這是一個專為劏房用戶設計的智能配電箱網頁應用程式模擬界面，提供業主和住戶兩個不同版本的操作介面。

## 系統架構

### 業主版本（房東）
主要功能：
- 多房間用電管理
- 自動電費計算
- 用電限制設置
- 整體用電分析
- 收費記錄管理
- 房間管理系統
- 異常用電警報
- 維修需求處理

### 住戶版本（租客）
主要功能：
- 個人用電監控
- 即時用電顯示
- 電費預估計算
- 智能節能建議
- 個人用電分析
- 繳費記錄查詢
- 故障報修功能
- 用電超標提醒

## 技術特點

- **安全性設計**
  - 用戶權限分級
  - 數據加密傳輸
  - 操作日誌記錄
  - 異常行為檢測

- **智能功能**
  - AI 用電行為分析
  - 智能節能建議
  - 預測性維護提醒
  - 自動故障診斷

- **用戶體驗**
  - 直覺操作界面
  - 多語言支持
  - 無障礙設計
  - 響應式布局

## 技術棧

- HTML5
- Tailwind CSS
- Chart.js
- Hammer.js

## 頁面說明

### 業主端
- `owner/dashboard.html` - 管理主頁
- `owner/rooms.html` - 房間管理
- `owner/billing.html` - 收費管理
- `owner/analytics.html` - 數據分析

### 住戶端
- `tenant/dashboard.html` - 個人主頁
- `tenant/usage.html` - 用電詳情
- `tenant/payment.html` - 繳費中心
- `tenant/support.html` - 支援服務

## 在線演示

訪問 [https://[你的GitHub用戶名].github.io/[倉庫名稱]/](https://[你的GitHub用戶名].github.io/[倉庫名稱]/) 查看在線演示。

## 本地運行

1. 克隆倉庫
```bash
git clone https://github.com/[你的GitHub用戶名]/[倉庫名稱].git
```

2. 使用瀏覽器打開對應版本的入口頁面：
   - 業主版本：`owner/index.html`
   - 住戶版本：`tenant/index.html`

## 開發說明

本項目採用前後端分離架構，前端使用 Tailwind CSS 進行樣式設計，使用 Chart.js 實現數據可視化，使用 Hammer.js 實現手勢控制。所有頁面都支援響應式設計，適配不同尺寸的設備。

### 開發重點
- 確保兩個版本的一致性體驗
- 注重數據安全和隱私保護
- 優化載入速度和性能
- 支持離線操作基本功能

## 授權協議

本項目採用 [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0) 授權條款。