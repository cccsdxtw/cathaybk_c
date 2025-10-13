# 📈 股票匯率 App

一款以 **即時資訊為核心** 的股票與匯率查詢應用程式，  
提供使用者快速、直觀的市場概覽。  
本專案原作為 **面試展示作品**，現已完成最終版本。

---

## 🎥 Demo 影片
👉 [點此觀看 App Demo](https://youtu.be/2YTVKWVG-NY?si=FttY6MRoKq3fpVG_)  
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
採用 Jetpack Compose 實作，介面簡潔直觀、效能優異。

---

## 🧩 技術架構

| 模組 | 技術 |
|------|------|
| **前端框架** | Kotlin + Jetpack Compose |
| **狀態管理** | StateFlow / ViewModel |
| **API 來源** | Yahoo Finance API、ExchangeRate.host API |
| **UI 設計** | Material 3 Design |
| **開發平台** | Android Studio |

---

## ⚙️ 安裝與執行

```bash
# 1️⃣ 下載專案
git clone https://github.com/yourname/stock-currency-app.git
cd stock-currency-app

# 2️⃣ 使用 Gradle 建置
./gradlew build

# 3️⃣ 執行 App
./gradlew installDebug
```

或於 **Android Studio** 中開啟專案，  
選擇目標模擬器後直接點擊 ▶️「Run」即可。


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
