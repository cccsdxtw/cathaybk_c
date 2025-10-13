# ✈️ Flight & Currency Tracker
**以 Kotlin 實作的航班與匯率查詢應用程式**

這是一款整合「航班查詢」與「匯率即時資訊」的 Android App，使用 Kotlin 原生開發。  
設計理念是讓使用者能在單一介面中，同時掌握航班動態與最新匯率變化，適合經常出差或旅遊的使用者。

---

## 🚀 功能特色

### ✈️ 航班查詢
- 可透過航班號、出發地或抵達地搜尋航班。  
- 顯示航班狀態（準時、延誤、取消等）。  
- 支援即時更新與簡潔的結果展示。

### 💱 匯率查詢
- 顯示主要貨幣的最新匯率。  
- 支援多國貨幣轉換與自訂常用清單。  
- 匯率資料會自動更新，離線時仍可顯示最後一次更新結果。

### 🎨 使用者介面
- 採用 Material Design 風格設計，介面簡潔直覺。  
- 深色／淺色模式自動切換（依系統設定）。  
- 數據以清晰的卡片與表格方式呈現。

---

## 🧩 技術架構

| 模組 | 說明 |
|------|------|
| 語言 | **Kotlin** |
| 架構模式 | MVVM (Model-View-ViewModel) |
| 網路層 | Retrofit + OkHttp |
| 資料處理 | Coroutines + Flow |
| JSON 解析 | Gson / Moshi |
| UI | XML + ViewBinding |
| API 來源 | Flight Data API、Exchange Rate API |
| 依賴管理 | Gradle |

---

## 💡 開發動機

此專案最初作為面試展示作品，  
重點在於展示 **Kotlin 原生開發能力、資料串接流程與介面設計能力**。  
在開發過程中，也嘗試提升使用體驗與資料更新效能，使應用更加實用化。

---

## 📸 專案展示影片
🔗 [YouTube - Flight & Currency Tracker Demo](https://youtu.be/Cp8UPhpHG6E?si=-VS8NuTVNIis5_1J)

---

## ⚙️ 安裝與執行方法

1️⃣ **下載專案**

```bash
git clone https://github.com/cccsdxtw/cathaybk_c.git
cd 你的專案名稱
```

2️⃣ **開啟專案**
- 使用 Android Studio (Arctic Fox 或以上版本) 開啟專案資料夾
- 確保已安裝 Kotlin Plugin 與 Gradle Plugin

3️⃣ **設定 API Key**
在 `local.properties` 或 `gradle.properties` 中新增以下內容（依實際 API 名稱調整）：

```properties
FLIGHT_API_KEY=你的航班API金鑰
CURRENCY_API_KEY=你的匯率API金鑰
```

4️⃣ **執行應用程式**
- 選擇目標模擬器或實體裝置
- 點擊「Run ▶」即可開始運行

---

## 🧭 專案結構
```
app/
├── data/
│   ├── api/
│   ├── model/
│   └── repository/
├── ui/
│   ├── flight/
│   ├── currency/
│   └── common/
├── viewmodel/
└── utils/
```

---

## 🏗️ 未來改進方向
- 加入航班延誤推播通知
- 匯率變化趨勢圖表化
- 支援多語系介面
- 使用 Room 實現離線快取

---

## 🧑‍💻 作者
Developed by **拉基蛋**  
📫 聯絡方式：hi0729@hotmail.com
