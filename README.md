# AGCT Café Data Analysis ☕📊

本專案為咖啡廳「AGCT Apartment」半年營運數據的分析與視覺化展示，涵蓋從資料清理、商品拆解、Python 視覺化到 Tableau 儀表板製作，完整呈現中小型餐飲業的數據洞察流程。
起始於清理後資料上傳、Python Notebook 建立、Tableau 儀表板整合，並已完成所有可視化與說明文件。

---

## 📁 專案結構
```
AGCT_Cafe_Data_Analysis/
├── data/
│ ├── AGCT_apriori_rules.csv ← Apriori分析後的數據
│ ├── AGCT_clean_orders.csv ← 清理後的訂單明細資料
│ └── AGCT_clean_items.csv ← 拆分後的商品品項明細
├── notebooks/
│ └── AGCT_analysis_visual.ipynb ← Python 分析與視覺化 Notebook
├── tableau/
│ └── AGCT_trends.twbx ← Tableau 儀表板（含三頁）
└── README.md ← 說明文件
```
---

## 📊 使用資料簡介

- 資料期間：2021/06/01 ～ 2021/11/30

---

## 🐍 Notebook 視覺化成果

使用 Python（Pandas + Matplotlib + Seaborn）進行：
- 客群類型統計圖
- 月營收與客單價趨勢
- 品項熱銷排行與組合視覺

📎 請見 `notebooks/AGCT_analysis_visual.ipynb`

---

## 📈 Tableau 儀表板展示

本專案包含三張互動式儀表板：

1. [📊 Sales Overview](https://public.tableau.com/views/AGCT_trends/SalesOverview)
2. [👥 Customer Insights](https://public.tableau.com/views/AGCT_trends/CustomerInsights)
3. [📦 Product Insights](https://public.tableau.com/views/AGCT_trends/ProductInsights)

🟡 點擊連結即可在 Tableau Public 上互動瀏覽。

---

## 💡 分析目標

- 探索顧客行為差異（新舊客、來客人數）
- 分析營收變動趨勢與平均客單價
- 發掘熱門商品與隱藏貢獻品項
- 提供數據驅動的營運建議（如高峰時段、座位利用、外帶佔比等）

---

## 🧠 作者與說明

Derek Ni（倪爾佑）｜NTU 圖資系 + 經濟輔系  
專注於數據分析、可視化、商業策略應用  
歡迎參觀我的 [Tableau 公開頁面](https://public.tableau.com/app/profile/derek.ni5275)

---
