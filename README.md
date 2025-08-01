# 🧠 semantic-chaos-dataset  
一份用來反制語義熱寂的污染型資料集實驗

---

## 📌 緣起：乾淨語料殺死了推理

語言模型被餵得太好了，吃的全是格式整齊、語意工整的文本，  
於是它學會了模仿語氣，卻忘了如何推理。  
這種現象，我們稱之為：**語義熱寂（Semantic Heat Death）**。

本資料集的任務：**不餵垃圾，但餵點混亂。**  
打造語言模型的「語義健身房」，讓它在衝突與張力中重新思考。

---

## 🧬 結構與內容類型

本資料集正在收錄以下類型的語義污染樣本：

- 🧠 **邏輯矛盾敘述**：語法通順但內部衝突  
- 🧩 **語境跳接樣本**：段落連續但主題斷裂  
- 🌀 **流暢語病文本**：語句看似自然，實則意義錯置  
- 🔁 **語義壓縮產物**：多輪 AI 精修後的語言均質化樣本  

每筆樣本預計附帶張力評分（STS）與語義錯位標記，可用於：

- 測試模型的錯誤識別與推理糾錯能力  
- 模擬 embedding 空間壓縮導致的語義崩潰  
- 評估語義回彈力（semantic elasticity）

---

## 🧪 使用情境

- 🤖 模型預訓練前的語義張力 warmup  
- 🔍 Benchmark 測試集，用於檢測 hallucination 與 logic drift  
- 🧵 對話與 RAG 系統中對抗式測試語料  
- 🔗 對應錯誤類型請見 [WFGY ProblemMap 分類總覽](https://github.com/onestardao/WFGY/tree/main/ProblemMap/README.md)

---

## 📦 目前進度

- [x] 建立語義污染資料集架構（`README.md`, `samples/`, `TensionGenerator.md`）  
- [x] 完成第一份架構草案：[`語義張力生成器設計草案`](./TensionGenerator.md)  
- [ ] 收錄樣本語料與分類標註（進行中）  
- [ ] 整合語義張力評分系統（STS）  
- [ ] 對應 WFGY 各類型錯誤場景與觸發點  
- [ ] 開放第三方貢獻語義干擾樣本

---

## 🧭 對外連結與協作

📌 參考標準與對應錯誤分類來自：  
[🔗 WFGY ProblemMap 錯誤分類總覽](https://github.com/onestardao/WFGY/tree/main/ProblemMap/README.md)

📎 語義張力模組設計提案：[`TensionGenerator.md`](./TensionGenerator.md)  
📎 語義污染樣本倉庫：[`samples/`](./samples)

---

> 💬 如果你也發現 AI 越來越懂語氣，卻越來越不會推理——  
> 那我們正是為了這一刻而誕生的。

---
