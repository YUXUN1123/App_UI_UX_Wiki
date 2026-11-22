---
title: "第三篇來源研究閱讀筆記 (03_Source_Reading_Notes)"
slug: "03_Source_Reading_Notes"
target_note: "[[03_Cognitive_Load_and_Gestalt]]"
created_at: 2026-11-22
tags:
  - UIUX
  - Ingest
  - ResearchNotes
---

# 第三篇 Wiki 研究閱讀筆記 (03_Source_Reading_Notes)

本筆記依據 [[AGENTS|AGENTS.md]] 之規範建立，記錄第三篇 Wiki 主題（`03_認知負荷與 Gestalt 視覺法則：大腦資訊處理與視覺組織機制`）之文獻查證、核心主張、可支持之論點、不能支持之推論及資料限制。

---

## 一、 [SRC-11] George A. Miller (1956)
* **書目資訊**：Miller, G. A. (1956). The magical number seven, plus or minus two: Some limits on our capacity for processing information. *Psychological Review*, 63(2), 81–97.
* **DOI**：`10.1037/h0043158`
* **文獻性質**：同儕審查開創性期刊論文。
* **主要主張**：
  1. 一維刺激的絕對判斷（Absolute Judgment）存在約 2.5 bits（約 7 個範疇）的通道容量限制（Channel Capacity）。
  2. 短期記憶的廣度主要受限於「資訊組塊（Chunks）」的數量，而非單純的資訊位元數（Bits）。透過重新編碼（Recoding），個體能將大量資訊打包成單一組塊，大幅提升有效容量。
* **可支持內容**：人腦透過「組塊化（Chunking）」提高短期資訊處理效率；資訊未經分組時容易造成處理瓶頸。
* **不能支持內容**：不能支持「7±2 是所有人的固定工作記憶容量」；絕對不可推論為「UI 選單項目不得超過 7 個」。
* **資料限制**：未存原始全文，依據公開摘要與權威文獻共識核對。

---

## 二、 [SRC-12] John Sweller (1988)
* **書目資訊**：Sweller, J. (1988). Cognitive load during problem solving: Effects on learning. *Cognitive Science*, 12(2), 257–285.
* **DOI**：`10.1207/s15516709cog1202_4`
* **文獻性質**：同儕審查開創性期刊論文。
* **主要主張**：傳統解題所採用的「手段目的分析（Means-ends analysis）」會佔用大量有限的工作記憶資源，阻礙學習者建構長期記憶中的「基模（Schemas）」。提出教學/介面設計應減少不必要的認知負荷。
* **可支持內容**：認知負荷理論（CLT）之基礎；工作記憶為認知處理的核心瓶頸；基模能使多項資訊元素自動化為單一元素。
* **資料限制**：早期 CLT 著重於數學與物理問題解題實驗，非針對數位行動介面。未存原始全文，依據文獻核對。

---

## 三、 [SRC-13] John Sweller, Paul Ayres, & Slava Kalyuga (2011)
* **書目資訊**：Sweller, J., Ayres, P., & Kalyuga, S. (2011). *Cognitive Load Theory*. New York: Springer.
* **DOI**：`10.1007/978-1-4419-8126-4` (ISBN: 978-1-4419-8125-7)
* **文獻性質**：重要理論學術專著（非最新專著，但為理論演進里程碑）。
* **主要主張**：系統化整理 CLT 理論演進。對經典三元模型中的「Germane Load」提出重要反思與修正，指出 Germane Load 並非獨立於 Intrinsic Load 之外的另一種實體負荷，而是指向致力於基模建構與自動化的「增益性處理歷程（Germane Processing）」。
* **可支持內容**：現代雙成分模型（總負荷主要由內在負荷與外在負荷構成，工作記憶資源分配於處理外在干擾或增益性基模建構）。
* **不能支持內容**：不得寫成適用所有情境的固定可加減數學公式。
* **資料限制**：受版權保護未存全文，依據專著目錄與權威文獻引證核對。

---

## 四、 [SRC-14] Richard C. Atkinson & Richard M. Shiffrin (1968)
* **書目資訊**：Atkinson, R. C., & Shiffrin, R. M. (1968). Human memory: A proposed system and its control processes. In K. W. Spence & J. T. Spence (Eds.), *The Psychology of Learning and Motivation* (Vol. 2, pp. 89–195). Academic Press.
* **DOI**：`10.1016/s0079-7421(08)60422-3`
* **文獻性質**：經典學術專著章節。
* **主要主張**：提出經典的多重儲存模型（Multi-store Model），將記憶系統劃分為感官記憶（Sensory Register）、短期儲存（Short-Term Store, STS）與長期儲存（Long-Term Store, LTS），並探討各層級的控制歷程（如複誦、編碼）。
* **可支持內容**：人腦記憶具有結構性階段劃分；短期儲存容量有限。
* **注意規範**：必須與 Baddeley 的工作記憶多成分模型保持區分，不將兩者混為一談。未存全文，依據學術共識核對。

---

## 五、 [SRC-15] Alan Baddeley (1992)
* **書目資訊**：Baddeley, A. (1992). Working memory. *Science*, 255(5044), 556–559.
* **DOI**：`10.1126/science.1736359`
* **文獻性質**：同儕審查權威綜述論文。
* **主要主張**：將短期記憶拓展為動態主動處理的「工作記憶（Working Memory）」，提出包含中央執行系統（Central Executive）、語音迴路（Phonological Loop）與視覺空間素描簿（Visuo-spatial Sketchpad）的多成分架構（後續擴充情境緩衝區）。
* **可支持內容**：工作記憶不僅是儲存空間，更是暫時維持與操弄資訊的處理工作檯，其視覺與聽覺通道各自具備處理瓶頸。
* **資料限制**：未存全文，依據論文核心架構核對。

---

## 六、 [SRC-16] Nelson Cowan (2001)
* **書目資訊**：Cowan, N. (2001). The magical number 4 in short-term memory: A reconsideration of mental storage capacity. *Behavioral and Brain Sciences*, 24(1), 87–114.
* **DOI**：`10.1017/s0140525x01003922`
* **文獻性質**：同儕審查靶子論文（Target Article）。
* **主要主張**：在嚴格控制干擾、排除資訊組塊與主動複誦策略的實驗條件下，純工作記憶（Pure storage capacity / Focus of attention）的真實容量約為 4 個組塊（範圍約 3 到 5 個）。
* **可支持內容**：人腦在無輔助策略下之極簡專注廣度；現代介面設計更需依賴視覺提示以減輕這 4 個組塊的維持壓力。
* **資料限制**：需明確說明其估計是在特定實驗控制條件下得出。未存全文，依據摘要核對。

---

## 七、 [SRC-17] Max Wertheimer (1923)
* **書目資訊**：Wertheimer, M. (1923). Untersuchungen zur Lehre von der Gestalt. II. *Psychologische Forschung*, 4(1), 301–350.
* **DOI**：`10.1007/BF00410640`
* **文獻性質**：同儕審查經典期刊論文（德文開創文獻）。
* **主要主張**：提出知覺組織法則（Laws of Perceptual Organization），包括接近性（Proximity）、相似性（Similarity）、良好連續性（Good Continuation/Direction）與閉合性（Closure）。
* **可支持內容**：人類知覺傾向自動將視野內的離散點線組織為群組與整體形態。
* **資料限制**：未存全文，依據英譯共識與現代知覺心理學標準核對。

---

## 八、 [SRC-18] Kurt Koffka (1935)
* **書目資訊**：Koffka, K. (1935). *Principles of Gestalt Psychology*. New York: Harcourt, Brace and Company. (現代重印版 ISBN: 9780415209625)
* **文獻性質**：經典學術專著。
* **主要主張**：系統化闡述格式塔心理學總體架構，特別是「好形態原則（Law of Prägnanz）」與圖地關係（Figure-Ground Organization）。視野會自發分化為主體與背景。
* **可支持內容**：圖地關係為視覺組織之根本；介面設計透過明暗與景深建立主次層級。
* **資料限制**：原書於 1935 年出版無 DOI，依據專著出版資訊與理論摘要核對。

---

## 九、 [SRC-19] Stephen E. Palmer (1992)
* **書目資訊**：Palmer, S. E. (1992). Common region: A new principle of perceptual grouping. *Cognitive Psychology*, 24(3), 436–447.
* **DOI**：`10.1016/0010-0285(92)90014-S`
* **文獻性質**：同儕審查實證期刊論文。
* **主要主張**：透過實證實驗確立了「共同區域原則（Common Region）」——當元素被封閉在同一個封閉邊界或背景區域內部時，會被知覺為同一組，且此效應在多數條件下能壓倒空間接近性。
* **可支持內容**：UI 中以卡片容器（Containers / Cards）或背景底色進行資訊分組的科學依據。
* **重要區分**：明確將 Common Region（具體封閉空間將元素圈起）與 Closure（不完整線條被大腦補齊）區分開來。
* **資料限制**：未存全文，依據公開摘要核對。
