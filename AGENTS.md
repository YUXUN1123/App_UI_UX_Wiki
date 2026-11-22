# 專案規範與 AI 代理行為準則 (AGENTS.md)

本文件為「為什麼有些 App 特別好用？——從使用者心理到 UI/UX 設計的完整解析」LLM Wiki 專案之最高規範。所有參與本專案的 AI 代理（Agents）與協同作業者均須嚴格遵守以下條款。

---

## 1. 核心原則與學術正確性 (Academic Rigor & Integrity)

### 1.1 零幻覺與可追溯性 (Zero Hallucination Policy)
- 嚴禁捏造任何研究數據、實驗樣本、作者年份、專利或學術引用。
- 凡提及心理學定律、人機互動理論或使用者測試結論，均須於 `sources/sources_index.md` 登錄，並於文中精準引用來源 ID。

### 1.2 語意層次嚴格區分
撰寫任何內容時，必須嚴格區分以下四種知識屬性，不得混淆：
1. **[實證研究事實]**：同儕審查（Peer-reviewed）期刊論文或學術專著之實驗結論。必須清楚標記實驗對象、情境條件與邊界限制。
2. **[官方產品規範]**：Apple HIG、Google Material Design、產品團隊官方 Engineering / Design Blog 發布之規格說明。
3. **[介面觀察]**：客觀描述當前 App（Google Maps、Notion、Duolingo）可被使用者重現的操作行為與視覺呈現。
4. **[分析與推論]**：基於理論對觀察結果做出的合理推導與假說。**必須清楚標註為分析推論，不得將推測視為已證實之事實**。特別是涉及產品內部運作機制（如推薦演算法、動態難度調節細節），若無官方公開技術文件或權威來源支持，**絕不可直接當成事實**。

### 1.3 重要概念的學理邊界與演進規範
- **Affordance 與 Signifier**：
  - **可供性 / 行動可能性（Affordance）**：定義為物件或介面實際提供給行動者的行動可能性（Action Possibilities），源自 Gibson 與 Norman 的定義，**嚴禁簡化為「預設用途」**。
  - **意符（Signifier）**：定義為「提示使用者如何操作的感知線索或標記」，用以傳達該處存在何種行動可能性。
- **Don Norman 設計原則之版本界定**：
  - 嚴格區分 Norman 在不同著作與年代的論述演進（例如 1988 年初版《The Psychology of Everyday Things》與 2013 年修訂版《The Design of Everyday Things: Revised and Expanded Edition》中對 Affordance 與 Signifier 的修正）。
  - **不可將不同時期或不同學者（如賈伯斯、尼爾森）的分類方式混為一談**。
- **認知負荷理論（Cognitive Load Theory）**：
  - 介紹 Sweller 等人經典的三元模型（內在負荷 Intrinsic、外在負荷 Extraneous、關聯負荷 Germane Load）。
  - **必須說明後續理論演進**：說明自 2010 年代後（Sweller, Kirschner, Kalyuga 等人研究），學界已將 Germane Load 重新界定為「工作記憶資源主動投入基模（Schema）建構與自動化的心理歷程（Germane Processing）」，而非獨立存在的負荷類型。避免將不同時期的學術模型混淆。
- **費茲定律（Fitts's Law）**：
  - 定位為人體運動目標獲取時間之數學模型，關注操作效率與互動區域尺寸/距離，**不得歸類為習慣養成理論**。
  - **必須明確標明所採用的公式版本**（例如 Fitts 1954 原始公式或 Shannon-MacKenzie 擴展公式 \(MT = a + b \log_2(\frac{D}{W} + 1)\)）及其適用條件（如一維/二維移動、游標 vs 觸控螢幕）。
- **米勒定律（Miller's Law）**：
  - 明確界定為「工作記憶容量限制與資訊組塊（Chunking）」，並非「UI 選單項目不得超過 7 個」的硬性介面規範。
- **Hook Model 與遊戲化**：
  - 探討行為改變與習慣養成機制的同時，必須深入檢視使用者自主權（Autonomy）與設計倫理，探討防成癮反思與外部動機排擠效應。

---

## 2. 原始資料管理與智財合規 (Copyright & Data Integrity)

1. **合法優先原則**：
   - 優先引用開放取用（Open Access）論文、官方公開技術白皮書及授權資料。
2. **授權限制與文件儲存**：
   - 僅可將公開授權、合法可下載之完整文件存放於 `rawpapers/`。
   - 若論文或專著受版權保護無法合法保存全文，**嚴禁下載或儲存未經授權之檔案**。此時僅在 `sources/sources_index.md` 完整登記 DOI、永久網址、書目資訊、引用章節頁碼及摘要。

---

## 3. sources_index.md 規格與登記規則

所有寫入 Wiki 的引用資料，必須先在 `sources/sources_index.md` 登記，欄位包含：
- **來源 ID (ID)**：格式如 `SRC-01`, `SRC-02`
- **來源名稱 (Title)**：完整標題
- **作者/機構 (Authors)**：主要作者或組織
- **發布日期 (Date)**：年份或確切日期
- **來源類型 (Type)**：同儕審查論文 / 經典專著 / 官方設計指南 / 智庫報告 / 實證測試
- **DOI / 永久連結 (DOI/URL)**：永久解析位址
- **引用章節/頁碼 (Pages)**：精確指出引用的章節或頁碼範圍
- **存取日期 (Access Date)**：檢索與驗證日期
- **已存原始檔 (Raw Stored)**：`Yes (rawpapers/檔名)` 或 `No (受版權保護，僅記摘要)`
- **對應 Wiki 篇目 (Target Note)**：雙向連結至對應筆記
- **來源限制與注意事項 (Notes)**：記載樣本侷限、實驗情境限制或版本差異

---

## 4. 寫作與格式規範 (Writing & Structure Specifications)

1. **核心產出架構**：
   - 專案由 **7 篇理論 Wiki ＋ 3 個產品案例研究（`case_studies/`） ＋ 1 份 HTML 教學簡報（`slides/`）** 組成。
   - 原規劃之第 8～10 篇不再作為獨立 Wiki 文章，而是將深度研究轉化為 `case_studies/` 專用研究資料，為簡報提供結構化實例。
2. **語言與術語**：
   - 全文使用繁體中文撰寫。
   - 專業名詞首次出現採「繁體中文（英文專業術語）」格式，後續維持一致統稱。
3. **Obsidian 雙向連結網絡**：
   - 核心概念與跨篇引用必須使用 `[[筆記名稱]]` 或 `[[筆記名稱#段落|顯示名稱]]` 雙向連結，建立語意圖譜。
4. **視覺呈現與 Mermaid 使用原則**：
   - **非強制繪圖**：僅在需要呈現心理迴圈、使用者操作旅程、資訊架構層級時使用 Mermaid。
   - 若表格、對比條列更能清晰表達（如 Do's & Don'ts 對照），優先使用表格或條列。
   - 介面範例一律採用文字分析並標記 `> 🖼️ [視覺與截圖規劃]` 預留位，留待簡報製作階段補充。
5. **單篇理論 Wiki 統一結構**：
   - YAML Frontmatter（含 title, slug, tags, aliases, created_at, module, related_notes, sources_referenced）
   - 核心摘要 (TL;DR)
   - 關鍵術語索引 (Glossary)
   - 1. 理論根基與心理學機制（含研究背景界定）
   - 2. 介面實踐與案例解析（含 Do's & Don'ts 及視覺預留位）
   - 3. 初學者行動指南（含 Checklist 與 Reflection）
   - 4. 引用來源與延伸閱讀（標示頁碼與 DOI）
6. **案例研究（`case_studies/`）結構**：
   - 與理論 Wiki 嚴格區隔，聚焦於產品研究與簡報素材萃取：
   - 包含：研究核心、系統分析（IA、心智模型、認知負荷、操作效率、回饋、限制）、介面實測觀察記錄、理論對照、教學簡報素材摘要、參考文獻。

---

## 5. 品質檢查閘門 (Five Quality Gates)

在產出或更新任何文章時，必須進行以下四項檢核：
- [ ] **來源稽核**：所有理論、數據均來自 `sources_index.md`，無未經證實的內部機制宣稱。
- [ ] **學術嚴謹**：Affordance、Cognitive Load、Fitts's Law 等術語精確無誤，未過度簡化。
- [ ] **前後一致**：各篇文章定義相互呼應，無邏輯矛盾。
- [ ] **連結與語法**：雙向連結與 Mermaid 代碼無死鏈、無語法錯誤。
- [ ] **簡報支援性**：TL;DR、核心結構與配圖說明完整，足以支援後續教學簡報萃取。
