# 📈 股票匯率 App

一款以 **即時資訊為核心** 的股票與匯率查詢應用程式，提供使用者快速、直觀的市場概覽。  
本專案原作為 **面試展示作品**，現已完成最終版本。

---

## 🎥 Demo 影片
👉 [點此觀看 App Demo](#)  
（可替換為實際影片連結，例如 YouTube 或雲端影片）

---

## 🧭 功能介紹

### 💹 股票資訊查詢  
即時顯示多檔股票的最新價格、漲跌幅與走勢圖。

### 💱 匯率查詢  
支援多國貨幣匯率對比，並提供即時換算結果。

### ⭐ 自訂追蹤清單  
可將常用的股票或貨幣加入關注清單，方便快速檢視。

### 🧩 清晰介面設計  
採用簡潔直觀的 UI 風格，重點資料一目了然。

---

## 🧩 技術架構

| 模組 | 技術 |
|------|------|
| **前端框架** | Flutter |
| **狀態管理** | Provider |
| **API 來源** | Yahoo Finance API、ExchangeRate.host API |
| **UI 設計** | Material Design 風格 |
| **開發平台** | Android Studio、VS Code |

---

## ⚙️ 安裝與執行

```bash
# 1️⃣ 下載專案
git clone https://github.com/yourname/stock-currency-app.git
cd stock-currency-app

# 2️⃣ 安裝依賴
flutter pub get

# 3️⃣ 執行 App
flutter run
```

或於 IDE（Android Studio / VS Code）中直接執行。

---

## 📚 專案結構

```
lib/
├── main.dart
├── models/        # 資料模型
├── services/      # API 與網路請求
├── screens/       # 各功能頁面
├── widgets/       # 共用元件
└── utils/         # 工具與常數
```

---

## 🚀 未來計畫

- [ ] 加入個人化投資組合功能  
- [ ] 新增暗黑模式與主題切換  
- [ ] 增加歷史走勢與統計分析功能  
- [ ] 支援更多匯率資料來源  

---

## 🧑‍💻 作者

由 **[拉基蛋]** 開發。  
此專案原作為 **面試展示用途**，現公開作為技術與設計實例。

---

## 🌟 授權 License

此專案採用 MIT License — 歡迎自由使用與修改。  
詳見 [LICENSE](LICENSE)。

---

> 💬 若覺得這個專案有幫助，歡迎幫我點個 ⭐ Star，或提出建議讓我持續改進！
