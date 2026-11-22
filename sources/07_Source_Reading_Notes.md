---
title: "第七篇來源研究閱讀筆記 (07_Source_Reading_Notes)"
slug: "07_Source_Reading_Notes"
target_note: "[[07_Usability_Testing_and_Heuristics]]"
created_at: 2026-11-22
tags:
  - UIUX
  - Ingest
  - ResearchNotes
---

# 第七篇 Wiki 研究閱讀筆記 (07_Source_Reading_Notes)

本筆記依據 [[AGENTS|AGENTS.md]] 之規範建立，記錄第七篇 Wiki 主題（`07_易用性測試與啟發式評估：驗證設計的科學方法`）之文獻查證、核心主張、數學模型邊界、可支持之論點、不能支持之推論及資料限制。

---

## 一、 [SRC-38] Jakob Nielsen (1994)
* **書目資訊**：Nielsen, J. (1994). Enhancing the Explanatory Power of Usability Heuristics. In *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems* (CHI '94, pp. 152–158). ACM.
* **DOI**：`10.1145/191666.191729`
* **文獻性質**：同儕審查頂級會議論文。
* **主要主張**：
  1. 對早先的啟發式清單（包含 1990 年版本及 249 個易用性問題資料庫）進行因子分析（Factor Analysis），淬煉出具備最高解釋力的「十大易用性原則（10 Usability Heuristics）」。
  2. 十大原則包含：系統狀態可見性、符合系統與真實世界對照、使用者控制與自由、一致性與標準、防錯、辨識重於回憶、彈性與使用效率、美感與簡約設計、協助使用者辨識診斷並從錯誤中復原、說明文件與支援。
* **可支持內容**：十大易用性原則之學術源頭、定義、各項原則內涵。
* **資料限制**：未存全文，依據公開摘要與 ACM 核心分類架構核對。

---

## 二、 [SRC-39] Jakob Nielsen & Rolf Molich (1990)
* **書目資訊**：Nielsen, J., & Molich, R. (1990). Heuristic Evaluation of User Interfaces. In *Proceedings of the SIGCHI Conference on Human Factors in Computing Systems* (CHI '90, pp. 249–256). ACM.
* **DOI**：`10.1145/97243.97281`
* **文獻性質**：同儕審查頂級會議論文。
* **主要主張**：
  1. 奠定「啟發式評估（Heuristic Evaluation）」之定義與流程：由多位獨立評估專家（通常為 3–5 位）依據一套既定準則審查介面，再彙整各專家發現之易用性缺陷。
  2. 明確區分啟發式評估屬於「專家評審法（Expert Review）」，特點是成本低、速度快（Discount Usability Engineering），但**絕不能等同於或完全取代真人使用者測試**。
* **可支持內容**：啟發式評估之定義、多專家獨立評審流程、專家評估與真人測試之本質區別。
* **資料限制**：未存全文，依據 ACM 公開論文核心主張核對。

---

## 三、 [SRC-40] John Brooke (1996)
* **書目資訊**：Brooke, J. (1996). SUS: A 'quick and dirty' usability scale. In P. W. Jordan, B. Thomas, B. A. Weerdmeester, & I. L. McClelland (Eds.), *Usability Evaluation in Industry* (Chapter 21, pp. 189–194). Taylor & Francis.
* **ISBN**：`978-0748404605`
* **文獻性質**：經典學術專著專章。
* **主要主張**：
  1. 提出著名的「系統易用性量表（System Usability Scale, SUS）」，由 10 題正反交替的 5 點李克特量表題構成。
  2. 計算邏輯：奇數題得分減 1，偶數題以 5 減得分，將 10 題轉換分相加後乘以 2.5，得出 0–100 的總體標準化量值。
  3. **關鍵注意**：SUS 分數是複合指標評分，**絕不是「百分比（Percentage）」**，不可直接視為百分之多少的使用者感到滿意；業界公認平均基準線約為 68 分。
* **可支持內容**：SUS 原始 10 題結構、評分轉換計算公式、非百分比特性、滿意度主觀量化標準。
* **資料限制**：未存全書，依據作者原始專章與公認統計標準核對。

---

## 四、 [SRC-41] K. Anders Ericsson & Herbert A. Simon (1993)
* **書目資訊**：Ericsson, K. A., & Simon, H. A. (1993). *Protocol Analysis: Verbal Reports as Data* (Revised Edition). MIT Press.
* **ISBN**：`978-0262550239`
* **文獻性質**：經典認知心理學與方法論專著。
* **主要主張**：
  1. 系統性奠定「放聲思考法（Think-Aloud Protocol / Concurrent Verbalization）」之認知科學理論基礎。
  2. 當受試者在執行任務當下將腦中所思口語化時（Level 1 & Level 2 Verbalization），反映的是當前處於「工作記憶（Working Memory）」中的即時資訊，不會造成顯著的認知歷程改變或失真。
  3. 相對地，若要求受試者事後解釋（Level 3 / Retrospective Rationalization），受試者往往會自動啟動事後合理化（Rationalization），造成回憶偏差。
* **可支持內容**：Think-Aloud 的即時性與認知合理性、放聲思考與事後訪談之區分。
* **資料限制**：學術專著，受版權保護未存全文，依據認知心理學經典方法論核對。

---

## 五、 [SRC-42] Joseph S. Dumas & Janice C. Redish (1999)
* **書目資訊**：Dumas, J. S., & Redish, J. C. (1999). *A Practical Guide to Usability Testing* (Revised Edition). Intellect Books.
* **ISBN**：`978-1841500201`
* **文獻性質**：經典專業實務手冊專著。
* **主要主張**：
  1. 易用性測試的五大核心特徵：主要目標是提升產品易用性；參與者代表真實使用者；參與者執行真實任務；觀察與記錄使用者的操作行為；分析資料以診斷問題並提出改善建議。
  2. 主持人（Facilitator）中立原則：不得給予暗示、不得指導操作、保持客觀觀察。
* **可支持內容**：易用性測試實務操作流程、任務腳本設計準則、主持人行為規範。
* **資料限制**：受版權保護未存全文，依據經典版本架構與業界操作標準核對。

---

## 六、 [SRC-43] Jakob Nielsen & Thomas K. Landauer (1993)
* **書目資訊**：Nielsen, J., & Landauer, T. K. (1993). A mathematical model of the finding of usability problems. In *Proceedings of the INTERACT '93 and CHI '93 Conference on Human Factors in Computing Systems* (CHI '93, pp. 206–213). ACM.
* **DOI**：`10.1145/169059.169166`
* **文獻性質**：同儕審查頂級實證研究與數學模型論文。
* **主要主張**：
  1. 提出易用性問題發現的泊松/二項分布數學預測模型：
     $$ProblemsFound(n) = N(1 - (1 - \lambda)^n)$$
     其中 $N$ 為系統中存在的易用性問題總數，$n$ 為測試使用者人數，$\lambda$ 為單一使用者平均發現問題的機率。
  2. 論文統計顯示多個研究的 $\lambda$ 平均約為 0.31；在此條件下，$n = 5$ 時：
     $$1 - (1 - 0.31)^5 \approx 84.7\% \approx 85\%$$
  3. **模型適用邊界與限制**：
     - 此結論僅在單一使用者發現率 $\lambda \approx 0.31$ 且使用者同質性高的情況下成立。
     - 若產品客群多元（如專家與新手），或針對複雜專業領域系統，$\lambda$ 往往遠低於 0.31，此時 5 位受試者遠不足以涵蓋 85% 的問題。
     - 該公式的核心倡導是「**小規模、多輪迭代測試（Iterative Testing）**」，而非「任何專案只要找 5 個人測一次就足夠」。
* **可支持內容**：5 人測試的數學公式模型、二項分布推導、參數 $\lambda$ 的意義與適用條件、破除「5 人神話」的學理依據。
* **資料限制**：未存全文，依據公開論文數學模型公式與 CHI 正式文獻核對。
