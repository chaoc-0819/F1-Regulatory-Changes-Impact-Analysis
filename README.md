# F1 重大規則變革對比賽競爭格局影響分析

> 作者：教育學院學士班 趙岑曄、王羿脩  

---

## 📘 專案簡介

本專案旨在分析 Formula 1（F1）賽事中四項重大制度變革對賽場競爭格局的影響。我們整合多個數據來源與人工智慧輔助分析工具，透過歷史數據檢驗這些制度調整是否如預期改善了比賽的公平性與觀賞性。

---

## 🔍 分析主題

1. **積分系統調整（2010 年起）**
2. **輪胎供應商統一（2011 年起）**
3. **引擎升級變革（2006 與 2014 年）**
4. **空氣動力學規則修改（2014、2017、2022 年）**

---

## 🛠 使用技術與工具

- **語言**：Python
- **模型**：ChatGPT、Gemini、Windsurf SWE-1-lite
- **資料來源**：
  - [Ergast API](https://ergast.com/mrd/)
  - [FastF1](https://theoehrly.github.io/Fast-F1/)
  - [Kaggle Dataset](https://www.kaggle.com/rohanrao/formula-1-world-championship-1950-2020)
  - Jolpica API（第三方）
  - F1 官方網站

---

## 📈 分析方法

1. 利用 AI 模型進行 prompt 優化與程式碼生成
2. 擷取與處理資料
3. 描述性統計分析（HHI 指數、完賽率、單圈時間等）
4. 可視化展示趨勢與分布（直方圖、堆疊圖、折線圖等）

---

## 📊 成果亮點

- 確認積分制度改變後高分集中現象更加嚴重
- 輪胎供應商統一後，單圈表現並未明顯改善
- V6 引擎初期可靠性下滑，但後期回穩
- 空氣力學變革中以 2017 年效益最佳，其他兩次影響有限

---

## 🤔 結論與反思

制度改革的理想雖為提升比賽公平性與可看性，實際效果卻因強隊主導與技術落差而未能如願。我們也反思資料來源多寡與模型建議的重要性，未來研究將聚焦於更精準的因果分析。

---

## 📂 專案結構

```
F1-regulation-impact/
├── README.md
├── data/
│   ├── kaggle_f1.csv
│   ├── ergast_api_data.json
│   └── ...
├── analysis/
│   ├── scoring_system.ipynb
│   ├── tyre_supplier.ipynb
│   ├── engine_upgrade.ipynb
│   └── aerodynamics.ipynb
├── charts/
│   ├── fig1_hhi.png
│   └── ...
└── report/
    └── final_report.md
```

---

## 📬 聯絡方式

若對本專案有任何問題或建議，歡迎聯絡作者：
- Email：cenye@nycu.edu.tw
- GitHub：[@cenyezhao](https://github.com/yourusername)

---

感謝閱讀，我們希望這份分析能帶來對 F1 賽事制度更多面向的理解與關注！
