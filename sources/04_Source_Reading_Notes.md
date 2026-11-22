---
title: "第四篇來源研究閱讀筆記 (04_Source_Reading_Notes)"
slug: "04_Source_Reading_Notes"
target_note: "[[04_Interaction_Efficiency_and_Behavior]]"
created_at: 2026-11-22
tags:
  - UIUX
  - Ingest
  - ResearchNotes
---

# 第四篇 Wiki 研究閱讀筆記 (04_Source_Reading_Notes)

本筆記依據 [[AGENTS|AGENTS.md]] 之規範建立，記錄第四篇 Wiki 主題（`04_操作效率、互動設計與行為心理：費茲定律與席克定律的實務應用`）之文獻查證、核心主張、數學公式版次、可支持之論點、不能支持之推論及資料限制。

---

## 一、 [SRC-20] Paul M. Fitts (1954)
* **書目資訊**：Fitts, P. M. (1954). The information capacity of the human motor system in controlling the amplitude of movement. *Journal of Experimental Psychology*, 47(6), 381–391.
* **DOI**：`10.1037/h0055392`
* **文獻性質**：同儕審查開創性期刊論文。
* **主要主張**：
  1. 借用 Shannon 資訊理論中的通道容量概念，將人類運動控制系統視為一個資訊傳輸通道。
  2. 提出著名的「難度指數（Index of Difficulty, ID）」原始公式：\(ID = -\log_2 \frac{W}{2A} = \log_2 \frac{2A}{W}\)（其中 \(A\) 為振幅/距離 Amplitude，\(W\) 為目標寬度 Width）。
  3. 移動時間（Movement Time, MT）與難度指數呈高度線性關係：\(MT = a + b \cdot ID\)。
* **可支持內容**：目標越遠、越小，選取時間越長；目標寬度與移動距離的相對比例決定操作難度。
* **不能支持內容**：Fitts 1954 原型公式在 \(2A < W\) 時會產生負值 ID，且最初僅針對一維實體筆尖點擊；不可直接套用於現代二維螢幕邊角無限大之特性。
* **資料限制**：未存原始全文，依據心理學經典文獻與實驗數據核對。

---

## 二、 [SRC-21] I. Scott MacKenzie (1992)
* **書目資訊**：MacKenzie, I. S. (1992). Fitts' law as a research and design tool in human-computer interaction. *Human–Computer Interaction*, 7(1), 91–139.
* **DOI**：`10.1207/s15327051hci0701_3`
* **文獻性質**：同儕審查權威綜述與模型修正論文。
* **主要主張**：
  1. 系統性回顧費茲定律在 HCI 領域的應用，指陳 Fitts 1954 與 Welford 1968 公式之數學侷限。
  2. 正式推廣並確立了 **Shannon-MacKenzie 擴展公式**：  
     \[
     ID = \log_2 \left(\frac{D}{W} + 1\right)
     \]  
     \[
     MT = a + b \cdot \log_2 \left(\frac{D}{W} + 1\right)
     \]  
     （其中 \(D\) 為距離 Distance，\(W\) 為沿移動方向的有效寬度 Width）。
  3. 此公式徹底解決了 \(D=0\) 或目標寬大於距離時 ID 出現負值的問題，並符合 Shannon 定理的第一公式形態。
* **可支持內容**：現代人機介面（滑鼠、觸控筆、觸控螢幕）之標準費茲定律公式依據；定義表現指數 \(IP = 1/b\)（Index of Performance 或 Throughput）。
* **資料限制**：未存全文，依據同儕審查核心論述核對。

---

## 三、 [SRC-22] W. E. Hick (1952)
* **書目資訊**：Hick, W. E. (1952). On the rate of gain of information. *Quarterly Journal of Experimental Psychology*, 4(1), 11–26.
* **DOI**：`10.1080/17470215208416600`
* **文獻性質**：同儕審查開創性期刊論文。
* **主要主張**：
  1. 測量在不同選項數量下受試者的選擇反應時間（Choice Reaction Time）。
  2. 當每個選項的出現機率均等時，反應時間（RT）與選項數量 \(n\) 呈對數關係：  
     \[
     RT = a + b \log_2(n + 1)
     \]  
     （\(+1\) 代表除了選出特定目標外，還包含「確認是否有刺激發生」的不確定性狀態）。
* **可支持內容**：選項數量增加時，決策時間以對數而非線性速度成長（選項從 2 增加到 4 的增幅，等同於從 4 增加到 8 的增幅）。
* **不能支持內容**：不得推論為「選項越少越好」；Hick 假設的是受試者完全理解選項且選項均等的情境，未考量視覺搜尋與分組架構。
* **資料限制**：未存全文，依據實驗理論核對。

---

## 四、 [SRC-23] Ray Hyman (1953)
* **書目資訊**：Hyman, R. (1953). Stimulus information as a determinant of reaction time. *Journal of Experimental Psychology*, 45(3), 188–196.
* **DOI**：`10.1037/h0056940`
* **文獻性質**：同儕審查實證期刊論文。
* **主要主張**：
  1. 拓展了 Hick 的研究，探討刺激出現「機率不均等（Unequal Probabilities）」時對反應時間的影響。
  2. 證實選擇反應時間是**刺激的資訊熵（Information Entropy, \(H\)）**的線性函數：  
     \[
     H = \sum_{i=1}^{n} p_i \log_2\left(\frac{1}{p_i}\right) = -\sum_{i=1}^{n} p_i \log_2 p_i
     \]  
     \[
     RT = a + b \cdot H
     \]  
  3. 當刺激機率分布不均勻時，系統的資訊熵較低，受試者的平均反應時間也較短。
* **可支持內容**：不等機率選項下的決策時間模型；高頻選項與低頻選項並存時的反應時間受資訊熵規範。
* **不能支持內容**：不能支持「單純在介面上調整選項排列順序（如將高頻前置）就能在數學上改變系統資訊熵」；高頻前置改善的是視覺搜尋效率，不可混為一談。
* **資料限制**：未存全文，依據文獻與資訊理論核對。

---

## 五、 [SRC-24] Apple Human Interface Guidelines: Inputs - Touch
* **書目資訊**：Apple Inc. (2024 / 持續維護). *Human Interface Guidelines: Touch*. Apple Developer Documentation.
* **永久網址**：[https://developer.apple.com/design/human-interface-guidelines/inputs/touch/](https://developer.apple.com/design/human-interface-guidelines/inputs/touch/)
* **來源性質**：官方人機互動設計規範文件。
* **主要規範**：
  1. 觸控目標（Touch Target / Hit Target）的建議最小尺寸為 **44 × 44 points**。
  2. 強調「視覺尺寸」與「點擊熱區（Hit Area）」的解耦——小圖示可透過擴展邊界 padding 達到 44pt 觸發區域，降低費茲定律中的操作難度。
* **可支持內容**：iOS/iPadOS 系統觸控按鈕規格之官方事實。
* **資料限制**：官方設計指南，文字偏向實務實作規範，非同儕審查心理學實驗。

---

## 六、 [SRC-25] Google Material Design: Touch targets
* **書目資訊**：Google LLC (2024 / 持續維護). *Material Design: Accessibility - Touch targets*. Material.io.
* **永久網址**：[https://m3.material.io/foundations/accessible-design/accessibility-basics#touch-targets](https://m3.material.io/foundations/accessible-design/accessibility-basics#touch-targets)
* **來源性質**：官方開源設計系統規範。
* **主要規範**：
  1. 觸控目標建議最小尺寸為 **48 × 48 dp**（在標準螢幕密度下相當於約 9mm 物理尺寸，符合人體指尖按壓範圍）。
  2. 觸控元件之間建議保留至少 **8 dp** 的空間距離，以防止誤觸鄰近元件。
* **可支持內容**：Android/Material Design 觸控標準與防誤觸約束機制。
* **資料限制**：官方線上工程規範。
