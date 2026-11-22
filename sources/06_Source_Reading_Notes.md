---
title: "第六篇來源研究閱讀筆記 (06_Source_Reading_Notes)"
slug: "06_Source_Reading_Notes"
target_note: "[[06_Design_Anti_Patterns_and_Dark_Patterns]]"
created_at: 2026-11-22
tags:
  - UIUX
  - Ingest
  - ResearchNotes
---

# 第六篇 Wiki 研究閱讀筆記 (06_Source_Reading_Notes)

本筆記依據 [[AGENTS|AGENTS.md]] 之規範建立，記錄第六篇 Wiki 主題（`06_好設計 vs. 壞設計：介面反模式與暗黑模式`）之文獻查證、核心主張、法律適用邊界、可支持之論點、不能支持之推論及資料限制。

---

## 一、 [SRC-32] Harry Brignull (2023)
* **書目資訊**：Brignull, H. (2023). *Deceptive Patterns: Exposing the Tricks Tech Companies Use to Control You*. Testimonium Ltd.
* **ISBN**：`978-1739014704`
* **文獻性質**：經典專業實務專著。
* **主要主張**：
  1. 梳理自 2010 年創立 `darkpatterns.org` 迄今的實踐演進，正式將術語由早期通俗的「Dark Patterns（暗黑模式）」推進至具備法律與監管色彩的「**Deceptive Patterns（欺瞞性設計 / 詐欺模式）**」。
  2. 剖析科技巨頭如何利用人類認知捷徑（如選擇慣性、視覺偏誤）掠奪使用者利益。
* **可支持內容**：Dark Patterns 創始定義、Deceptive Patterns 的術語流變、Roach Motel、Confirmshaming、Forced Continuity 等經典模式之源頭界定。
* **資料限制**：經典業界專著，受版權保護未存原始全文，依據專著出版資訊與官方概念庫核對。

---

## 二、 [SRC-33] Colin M. Gray et al. (2018)
* **書目資訊**：Gray, C. M., Kou, Y., Battles, B., Hoggatt, J., & Toombs, A. L. (2018). The Dark (Patterns) Side of UX Design. In *Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems* (Paper No. 534, pp. 1–14). ACM.
* **DOI**：`10.1145/3173574.3174108`
* **文獻性質**：同儕審查頂級人機互動（CHI）會議實證論文。
* **主要主張**：
  1. 確立學術界對暗黑模式的第一套系統化分類框架，提煉出**五大核心原語（Primary Dark Pattern Strategies）**：
     - **Nagging (騷擾)**：重複打斷使用者正常操作流程，強迫其做決定（如重複彈出開啟通知彈窗）。
     - **Obstruction (阻礙)**：人為製造操作摩擦力，讓特定操作（如取消訂閱、刪除帳號）異常困難。
     - **Sneaking (潛藏)**：隱藏、延遲揭露或偽裝與使用者直接相關的重要資訊（如結帳偷加附加費）。
     - **Interface Interference (介面干擾)**：利用不對稱的視覺層級、預設勾選或預設選項，誘導特定選擇。
     - **Forced Action (強制行動)**：強迫使用者必須完成某一無關操作，方能繼續使用服務。
* **可支持內容**：五大暗黑模式策略之學術定義與機制分類。
* **資料限制**：未存全文，依據 ACM 官方核心論文分類與同儕審查文獻核對。

---

## 三、 [SRC-34] Arunesh Mathur et al. (2019)
* **書目資訊**：Mathur, A., Acar, G., Friedman, M., Lucherini, E., Mayer, J., Chetty, M., & Narayanan, A. (2019). Dark Patterns at Scale: Findings from a Crawl of 11K Shopping Websites. *Proceedings of the ACM on Human-Computer Interaction*, 3(CSCW), Article 81, 1–32.
* **DOI**：`10.1145/3359183`
* **文獻性質**：同儕審查頂級實證研究期刊論文。
* **主要主張**：
  1. 對約 1.1 萬個購物網站進行大規模自動化爬蟲分析，共辨識出 1,818 個暗黑模式實例，分布於 1,254 個網站中，約佔受檢網站之 11.1%。
  2. 揭示常見類型：急迫感（Urgency，如倒數計時器）、稀缺性（Scarcity）、預選項目（Pre-selection）等。
* **可支持內容**：暗黑模式在真實電商領域的普及率量化數據與客觀實例。
* **資料限制**：聚焦於線上電商平台，研究採 2019 年爬蟲數據。未存全文，依據論文公開摘要核對。

---

## 四、 [SRC-35] OECD (2022)
* **書目資訊**：OECD. (2022). *Dark commercial patterns* (OECD Digital Economy Papers, No. 336). Paris: OECD Publishing.
* **DOI**：`10.1787/44f5e846-en`
* **文獻性質**：國際政府組織權威政策與研究報告。
* **主要主張**：
  1. 從消費者行為經濟學與認知心理學視角，論證暗黑模式如何剝奪消費者的「自由與知情決策權（Free and Informed Decision）」。
  2. 剖析心理機制：利用雙系統思維中的 System 1 直覺捷徑、現時偏誤（Present Bias）與損失趨避（Loss Aversion）。
* **可支持內容**：暗黑模式跨國危害之政策與行為經濟學分析；消費者保護框架。
* **資料限制**：官方公開發布之政策研究報告全文。

---

## 五、 [SRC-36] Federal Trade Commission (FTC) (2022)
* **書目資訊**：Federal Trade Commission (FTC). (2022). *Bringing Dark Patterns to Light: An FTC Staff Report*. FTC Reports.
* **永久網址**：[https://www.ftc.gov/reports/bringing-dark-patterns-light](https://www.ftc.gov/reports/bringing-dark-patterns-light)
* **文獻性質**：美國聯邦政府執法與調查官方報告。
* **主要主張**：
  1. 梳理 FTC 歷年執法實務，將重點打擊之暗黑模式聚焦於四大方向：
     - **偽裝廣告 (Disguised Ads)**：例如將商業業配包裝為客觀獨立新聞報導或搜尋結果。
     - **滴灌定價 / 隱藏費用 (Drip Pricing / Hidden Fees)**：結帳流程逐層加碼未預期之額外收費。
     - **取消訂閱迷宮 (Obstacle Mazes / Easy to Subscribe, Hard to Cancel)**：一鍵即可訂閱，退訂卻要求打客服電話或層層阻攔。
     - **隱私操控與虛假選擇 (Privacy Dark Patterns)**。
* **可支持內容**：美國聯邦執法視角下的典型詐欺模式與實務案例。
* **資料限制**：官方公開調查報告全文。

---

## 六、 [SRC-37] Regulation (EU) 2022/2065 (Digital Services Act, DSA) Article 25
* **書目資訊**：European Parliament and Council of the European Union. (2022). Regulation (EU) 2022/2065 of the European Parliament and of the Council of 19 October 2022 on a Single Market For Digital Services (Digital Services Act). *Official Journal of the European Union*, L 277, 1–102.
* **永久法規網址**：[https://eur-lex.europa.eu/eli/reg/2022/2065/oj](https://eur-lex.europa.eu/eli/reg/2022/2065/oj)
* **文獻性質**：歐盟正式立法法規（截至 2026 年已全面生效實施中）。
* **核心條款 (Article 25(1))**：
  > "Providers of online platforms shall not design, organise or operate their online interfaces in a way that deceives or manipulates the recipients of their service or in a way that otherwise materially distorts or impairs the ability of the recipients of their service to make free and informed decisions."
  > （線上平台提供者不得以欺騙或操控其服務接收者之方式，或以實質扭曲或損害其服務接收者做出自由且知情決策之能力的方式，設計、組織或營運其線上介面。）
* **可支持內容**：全球最具代表性的暗黑模式明文法定禁止條款。
* **法律適用邊界與限制（嚴肅規範）**：
  1. 適用對象為在歐盟境內提供服務之線上平台（Online Platforms）；
  2. 依 Article 25(2)，其不適用於已由歐盟《不公平商業行為指令 (UCPD) 2005/29/EC》或《通用資料保護條例 (GDPR) 2016/679》所專門規範之商業詐欺或純個資同意事項，DSA 扮演法規補充之安全網角色；
  3. 不得將歐盟單一區域法規混寫為全球所有網站皆一體適用的法律。
