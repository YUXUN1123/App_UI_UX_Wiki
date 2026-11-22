---
title: "第五篇來源研究閱讀筆記 (05_Source_Reading_Notes)"
slug: "05_Source_Reading_Notes"
target_note: "[[05_Information_Architecture_and_Flow]]"
created_at: 2026-11-22
tags:
  - UIUX
  - Ingest
  - ResearchNotes
---

# 第五篇 Wiki 研究閱讀筆記 (05_Source_Reading_Notes)

本筆記依據 [[AGENTS|AGENTS.md]] 之規範建立，記錄第五篇 Wiki 主題（`05_資訊架構、導覽設計與使用者旅程：打造不迷航的數位地圖`）之文獻查證、核心主張、研究方法區分、可支持之論點、不能支持之推論及資料限制。

---

## 一、 [SRC-26] Louis Rosenfeld, Peter Morville, & Jorge Arango (2015)
* **書目資訊**：Rosenfeld, L., Morville, P., & Arango, J. (2015). *Information Architecture: For the Web and Beyond* (4th ed.). Sebastopol, CA: O'Reilly Media.
* **ISBN**：`978-1491911686`
* **文獻性質**：經典專業權威專著（資訊架構領域代表作「北極熊書」）。
* **主要主張**：
  1. 資訊架構（IA）被定義為：共享資訊環境的結構化設計；數位、實體與跨通道生態系統中內容的組織、標籤、搜尋與導覽系統的綜合體現。
  2. 系統化確立資訊架構的**四大核心支柱系統**：
     - **組織系統 (Organization Systems)**：內容如何分群與分類（階層式、時間式、字母式、主題式）。
     - **標籤系統 (Labeling Systems)**：如何用清晰詞彙代表資訊集合（導覽標籤、索引字彙）。
     - **導覽系統 (Navigation Systems)**：使用者如何在空間中移動並知悉當前位置（全域、區域、情境、麵包屑導覽）。
     - **搜尋系統 (Search Systems)**：使用者如何主動檢索資訊（搜尋介面、篩選器、演算法與結果呈現）。
* **可支持內容**：資訊架構的四大系統定義與關係；資訊組織模式分類；導覽層級與深度廣度平衡。
* **資料限制**：經典專著，受版權保護未存原始全文，依據專著出版目錄與權威架構核對。

---

## 二、 [SRC-27] Peter Morville (2005)
* **書目資訊**：Morville, P. (2005). *Ambient Findability: What We Find Changes Who We Become*. Sebastopol, CA: O'Reilly Media.
* **ISBN**：`978-0596007652`
* **文獻性質**：經典專業學術專著。
* **主要主張**：
  1. 提出**可尋性（Findability）**是好體驗的根本基石：一件物件或資訊哪怕品質再高，如果使用者「找不到它」，它在實質上就等同於不存在。
  2. 探討數位空間中的尋路行為（Wayfinding），指出使用者在資訊環境中穿梭時，強烈依賴明確的路標、方向指示與當前位置標記。
* **可支持內容**：Findability 的重要性；導覽設計中必須提供「我現在在哪裡」、「我可以去哪裡」的空間定位感。
* **資料限制**：未存全文，依據出版資訊與核心理論核對。

---

## 三、 [SRC-28] Jesse James Garrett (2011)
* **書目資訊**：Garrett, J. J. (2011). *The Elements of User Experience: User-Centered Design for the Web and Beyond* (2nd ed.). Berkeley, CA: New Riders.
* **ISBN**：`978-0321683687`
* **文獻性質**：經典專業權威專著。
* **主要主張**：
  1. 提出著名的「UX 五層要素模型」：戰略層（Strategy）→ 範圍層（Scope）→ **結構層（Structure）** → 框架層（Skeleton）→ 表現層（Surface）。
  2. 在「結構層」中，精準區分了面向功能的**互動設計（Interaction Design）**與面向內容的**資訊架構（Information Architecture）**。
* **可支持內容**：資訊架構在整體 UX 設計流程中的結構層定位；清楚分離 IA 與表層 UI 視覺之本質差異。
* **資料限制**：受版權保護未存全文，依據經典五層模型核對。

---

## 四、 [SRC-29] Peter Pirolli & Stuart K. Card (1999)
* **書目資訊**：Pirolli, P., & Card, S. (1999). Information foraging. *Psychological Review*, 106(4), 643–675.
* **DOI**：`10.1037/0033-295X.106.4.643`
* **文獻性質**：同儕審查開創性期刊論文。
* **主要主張**：
  1. 提出**資訊覓食理論（Information Foraging Theory）**，將人類在資訊環境中尋找目標的行為，類比為動物在自然界中捕食獵物的最適化覓食策略（Optimal Foraging Theory）。
  2. 提出**資訊氣味（Information Scent）**概念：使用者在瀏覽網頁或介面時，會依據連結文字、圖示與摘要等近端線索（Proximal Cues），評估點擊該連結能否引導至目標內容的潛在收益。若資訊氣味微弱或具備誤導性，使用者會果斷放棄路徑或產生迷航。
* **可支持內容**：標籤系統（Labeling）與連結文字設計的人因心理學依據；使用者如何評估下一步點擊價值。
* **資料限制**：未存全文，依據同儕審查核心理論核對。

---

## 五、 [SRC-30] Nielsen Norman Group (NN/g) - Card Sorting
* **書目資訊**：Nielsen Norman Group (NN/g). (2019 / 持續維護). *Card Sorting: Pushing Users Beyond Terminology to Categories*. NN/g Articles.
* **永久網址**：[https://www.nngroup.com/articles/card-sorting-pushing-users/](https://www.nngroup.com/articles/card-sorting-pushing-users/)
* **來源性質**：專業研究機構方法論專文（非同儕審查論文）。
* **主要主張**：
  1. 卡片分類法（Card Sorting）主要用於**探索使用者心智模型中如何將內容進行分類與命名**。
  2. 區分開放式（Open）、封閉式（Closed）與混合式（Hybrid）卡片分類。
  3. 警示研究中的「關鍵字匹配偏誤（Keyword Matching）」——卡片標籤必須保持中立，避免使用者僅依字面相似性堆疊分類。
* **可支持內容**：Card Sorting 的研究目的、分類與執行限制。
* **嚴格區分**：**Card Sorting 是前期探索使用者分類心智的工具，非驗證既有導覽結構的工具**。

---

## 六、 [SRC-31] Nielsen Norman Group (NN/g) - Tree Testing
* **書目資訊**：Nielsen Norman Group (NN/g). (2014 / 持續維護). *Tree Testing: Fast, Iterative Evaluation of Menu Labels and Categories*. NN/g Articles.
* **永久網址**：[https://www.nngroup.com/articles/tree-testing/](https://www.nngroup.com/articles/tree-testing/)
* **來源性質**：專業研究機構方法論專文（非同儕審查論文）。
* **主要主張**：
  1. 樹狀測試（Tree Testing）常被稱為「反向卡片分類」，專門用於**在完全剝除視覺排版、顏色與 UI 樣式的純文字階層結構（Tree）中，量化驗證既有選單標籤與分類的可尋性（Findability）**。
  2. 透過設定真實尋找任務，測量任務成功率（Success Rate）、直接度（Directness）與操作時間。
* **可支持內容**：Tree Testing 的研究目的、無 UI 驗證特性與指標。
* **嚴格區分**：**Tree Testing 用於驗證既有分類架構是否好用，不可與 Card Sorting 探索使用者心智的目的顛倒**。
