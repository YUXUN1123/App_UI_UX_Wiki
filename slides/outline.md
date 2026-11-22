# 《為什麼有些 App 特別好用？》HTML 互動式教學簡報大綱

> **副標題**：從使用者心理到 UI/UX 設計的完整解析  
> **英文標題**：Why Are Some Apps So Easy to Use? From Cognitive Psychology to UI/UX Principles  
> **對象目標**：無 UI/UX 專業背景之一般初學者與跨領域學習者  
> **知識底座**：基於 App UI/UX Wiki 7 篇理論 Wiki、3 篇產品案例研究與 `sources_index.md` (SRC-01 ~ SRC-54)

---

## 頁面結構規劃（共 32 頁）

### 【開場與導引】
- **Slide 01: 封面頁 (Title Slide)**
  - 核心標題、副標題、主講定位、開始探索按鈕。
- **Slide 02: 學習地圖與目錄 (Table of Contents)**
  - 七大章節直覺導引、章節一鍵跳轉、學習目標預覽。

---

### 【第一章：從日常生活認識 UI/UX】（對應 Wiki 01）
- **Slide 03: 開場之問——為什麼有些 App 特別順手，有些卻讓人抓狂？**
  - 生活情境對比（叫外送、租借共享單車、網購結帳卡住）。
  - 引導思考：「好用」究竟是一種玄學，還是經過精密計算的科學？
- **Slide 04: UI 與 UX 的本質差異——甜甜圈模型**
  - UI（User Interface，使用者介面）：糖霜、顏色、外觀、視覺元件。
  - UX（User Experience，使用者體驗）：麵體口感、飽足感、購買流程與整體情緒。
  - 引用：[[sources/sources_index#SRC-04|Norman & Nielsen (1998)]]「典範體驗的第一要件是無障礙且不費吹灰之力地滿足核心需求」。
- **Slide 05: 什麼是「好的體驗」？——ISO 9241-11 與體驗蜂巢**
  - 易用性三大支柱：有效性（Effectiveness）、效率（Efficiency）、滿意度（Satisfaction）([[sources/sources_index#SRC-02|ISO 9241-11:2018]])。
  - Morville 的 UX 蜂巢思考（Useful, Usable, Desirable, Findable... [[sources/sources_index#SRC-05|Morville 2004]]）。
  - 初學者啟示：漂亮介面只是及格線，無痛達成目標才是核心。

---

### 【第二章：使用者的大腦如何理解介面？】（對應 Wiki 02, 03）
- **Slide 06: 人腦的心理濾鏡——心智模型（Mental Models）**
  - 概念模型 vs. 心智模型 vs. 系統映像（System Image [[sources/sources_index#SRC-10|Norman 2013]]）。
  - 生活實例：電梯關門鍵、冷氣溫度調節的心理預期落差。
  - 執行鴻溝（Gulf of Execution）與評估鴻溝（Gulf of Evaluation）。
- **Slide 07: 易混淆概念澄清——可供性 (Affordance) vs. 意符 (Signifier)**
  - Affordance（行動可能性 [[sources/sources_index#SRC-08|Gibson 1979]]）：環境客觀賦予的物理潛能（螢幕可以被摸、玻璃可以透光）。
  - Signifier（提示意符 [[sources/sources_index#SRC-10|Norman 2013]]）：傳達操作方式的感知線索（藍色凸起按鈕暗示「點擊這裡」）。
  - 初學者常見誤區：「沒有所謂『介面預設用途』，圖示與標籤都是 Signifiers」。
- **Slide 08: 讓操作自然發生——Mapping, Feedback & Constraints**
  - 自然對應（Natural Mapping）：瓦斯爐開關位置對照。
  - 操作回饋（Immediate Feedback）：點擊後的視覺、聲音或震動回應。
  - 物理與邏輯約束（Constraints）：插頭防呆方向、未填表單前按鈕置灰。
- **Slide 09: 大腦的記憶瓶頸——工作記憶與認知負荷 (CLT)**
  - 工作記憶的極限容量：Miller 7±2 ([[sources/sources_index#SRC-11|Miller 1956]]) 到 Cowan 的純容量 4 組塊 ([[sources/sources_index#SRC-16|Cowan 2001]])。
  - 認知負荷理論（CLT [[sources/sources_index#SRC-12|Sweller 1988]], [[sources/sources_index#SRC-13|2011]]）：
    - 內在負荷（Intrinsic Load，任務本質難度）
    - 外在負荷（Extraneous Load，糟糕排版帶來的無謂負擔——UI 必須全力消除！）
    - 增益性處理（Germane Processing，建立心智基模的學習歷程）。
- **Slide 10: 大腦如何自動分組？——格式塔視覺原則 (Gestalt)**
  - 接近性（Proximity）與相似性（Similarity [[sources/sources_index#SRC-17|Wertheimer 1923]]）。
  - 圖地關係（Figure-Ground [[sources/sources_index#SRC-18|Koffka 1935]]）與共同區域（Common Region [[sources/sources_index#SRC-19|Palmer 1992]]）。
  - 介面實務：卡片化容器（Card UI）如何讓大腦一秒辨識關聯資訊。
- **Slide 11: 互動小測驗 (1)——大腦心理學即時挑戰**
  - 題目：辨析「點擊按鈕變色」與「按鈕上的立體陰影」分別屬於 Norman 的哪項原則？即時互動判斷反饋。

---

### 【第三章：怎樣的操作才有效率？】（對應 Wiki 04, 05）
- **Slide 12: 物理操作的數學定律——費茲定律 (Fitts's Law)**
  - 公式解構：$MT = a + b \log_2(D/W + 1)$ ([[sources/sources_index#SRC-21|MacKenzie 1992]])。
  - 核心變數：距離 $D$（愈近愈快）、目標尺寸 $W$（愈大愈容易點中）。
  - 實務應用：行動端單手持機的「拇指舒適區（Thumb Zone）」、無界邊緣效應（螢幕四角與底部 $D=0, W=\infty$）。
- **Slide 13: 決策時間的對數規律——席克－海曼定律 (Hick-Hyman Law)**
  - 公式解構：$RT = a + b \log_2(n + 1)$ ([[sources/sources_index#SRC-22|Hick 1952]])。
  - 決策疲勞與選擇癱瘓：選項愈多，思考時間呈對數暴增。
  - 介面解方：選項分組、預設推薦（Default Option）、漸進式揭露。
- **Slide 14: 資訊空間的建築學——資訊架構 (IA) 四大支柱**
  - 資訊架構經典「北極熊書」([[sources/sources_index#SRC-26|Rosenfeld, Morville, & Arango 2015]])：
    - 組織系統（階層式、時間軸、主題式）
    - 標籤系統（說人話，避免工程術語）
    - 導覽系統（全域標籤列、麵包屑、錨點）
    - 搜尋系統（模糊比對、自動補全、多維篩選）。
- **Slide 15: 引導使用者的操作旅程——使用者流程 (User Flow)**
  - 快樂路徑（Happy Path）vs. 例外分支（Error / Fallback Paths）。
  - 資訊氣味（Information Scent [[sources/sources_index#SRC-29|Pirolli & Card 1999]]）：讓使用者嗅得到正確前進的線索。
  - 案例對照：傳統 5 頁結帳填表 vs. 現代一頁式流暢結帳。

---

### 【第四章：好的設計與不好的設計】（對應 Wiki 06）
- **Slide 16: 什麼是暗黑模式 (Dark / Deceptive Patterns)？**
  - 概念起源：Harry Brignull ([[sources/sources_index#SRC-32|Brignull 2023]]) 與 CHI 學術框架 ([[sources/sources_index#SRC-33|Gray et al. 2018]])。
  - 定義：利用人類認知偏誤（System 1 直覺、損失趨避、現狀偏誤），誘使使用者做出非其本意的利益受損決策。
- **Slide 17: 常見暗黑模式手法深度拆解**
  - 蟑螂捕鼠器（Roach Motel，易入難出）
  - 確認羞辱（Confirmshaming，「我不要優惠，我是笨蛋」）
  - 誤導視覺（False Hierarchy / Visual Interference）
  - 滴灌定價（Drip Pricing，結帳才加收手續費）。
- **Slide 18: 好設計 vs. 壞設計對照實驗室 (Visual Comparison)**
  - 模擬介面對比：
    - 壞設計：充滿情緒勒索彈窗、灰色極小退訂鍵、預選保險勾選框。
    - 好設計：清楚透明的方案說明、對稱平衡的按鈕權重、退訂一鍵完成。
  - 倫理與法規：歐盟數位服務法 ([[sources/sources_index#SRC-37|DSA Article 25]]) 明文禁止欺瞞性介面。

---

### 【第五章：從三個 App 看設計原則如何實際運用】（對應 Case Studies 01, 02, 03）
- **Slide 19: 經典案例串聯導引——三大典範的教學定位**
  - Google Maps：解決「極致複雜空間資訊的認知減負與即時導航」。
  - Notion：解決「模組化自由度與初學者操作複雜度的平衡」。
  - Duolingo：解決「碎片化時間激勵、即時回饋與遊戲化倫理」。
- **Slide 20: 案例一：Google Maps——真實世界數位化的空間指引**
  - 產品挑戰：數十億空間 POI 與高速移動情境下的認知超載。
  - 亮點 1：情境驅動雙層架構（導航開始時全域分頁動態退場，收斂為 3 大駕駛卡片）。
  - 亮點 2：自我中心座標前向映射（Heading-up [[sources/sources_index#SRC-45|Klippel et al. 2006]]），消除「心智旋轉」。
  - 亮點 3：多尺度製圖過濾（[[sources/sources_index#SRC-44|Roth 2013]]）與高對比路徑圖地關係。
- **Slide 21: Google Maps 的即時回饋與極限挑戰**
  - 偏離路徑平滑重算、GPS 精度圓與方向扇形光錐。
  - 限制與邊界：立體高架橋 Z 軸高度判定落差、地下商場訊號中斷。
- **Slide 22: 案例二：Notion——模組化積木與漸進式揭露**
  - 產品挑戰：高自由度帶來的「空白畫布恐懼」與早熟承諾（Premature Commitment [[sources/sources_index#SRC-50|Green & Petre 1996]]）。
  - 亮點 1：積木概念模型（Everything is a Block [[sources/sources_index#SRC-49|Notion 2024]]），打破紙張隱喻。
  - 亮點 2：斜線指令 `/` 漸進式揭露，維持畫面極致簡約。
  - 亮點 3：反白就地浮動工具列（Fitts's Law 縮短指標距離 $D$）。
- **Slide 23: Notion 的資訊架構與組織成本**
  - 頁面即容器（Page as Container，兼具文章與無限嵌套特性，非傳統純資料夾）。
  - 全域麵包屑導覽解答「我在哪裡」。
  - 限制與代價：高黏滯性（後期資料重構維護成本）與視覺次要標記混亂。
- **Slide 24: 案例三：Duolingo——微學習路徑與多感官回饋**
  - 產品挑戰：語言學習枯燥反人性、高放棄率。
  - 亮點 1：單向序列關卡路徑（The Path [[sources/sources_index#SRC-53|Duolingo 2023]]），消除尋路選擇障礙。
  - 亮點 2：任務微型化（Bite-sized Scaffolding）與單字積木氣泡（辨識重於回憶）。
  - 亮點 3：多模態即時正反回饋（綠色底條 + 和弦音 + 觸覺震動；錯題不扣分留待單元末重做）。
- **Slide 25: Duolingo 的遊戲化雙面刃與倫理反思**
  - PBL 激勵機制（連勝火苗 Streak、每週聯盟、限時雙倍經驗 [[sources/sources_index#SRC-51|Dicheva et al. 2015]], [[sources/sources_index#SRC-54|Eyal 2014]]）。
  - 批判性反思：過度辯證效應（Overjustification Effect [[sources/sources_index#SRC-52|Deci et al. 1999]]）——外在獎勵可能侵蝕內在求知動機，導致使用者為保住紀錄而「刷簡單題」。
  - 警思：開啟次數與高留存率不等於真正掌握外語。
- **Slide 26: 互動小測驗 (2)——三大案例情境對照挑戰**
  - 題目：若電商 App 想降低使用者篩選 50 種標籤時的認知負擔，最應借鑑 Notion 的哪項設計？（漸進式揭露 / 斜線指令分類）。

---

### 【第六章：如何判斷一個 App 是否好用？】（對應 Wiki 07）
- **Slide 27: 科學評估設計——啟發式評估 vs. 易用性測試**
  - 設計者的致命盲點：知識的詛咒（Curse of Knowledge）與虛假共識效應。
  - 啟發式評估（Heuristic Evaluation [[sources/sources_index#SRC-39|Nielsen & Molich 1990]]）：3–5 位專家審查，非真人測試。
  - 易用性測試（Usability Testing [[sources/sources_index#SRC-42|Dumas & Redish 1999]]）：觀察真實使用者的客觀行為，採用放聲思考法（Think-Aloud [[sources/sources_index#SRC-41|Ericsson & Simon 1993]]）。
- **Slide 28: Jakob Nielsen 十大易用性啟發式原則精華速查**
  - 1. 系統狀態可見性
  - 2. 符合真實世界對照
  - 3. 使用者控制與自由（緊急出口）
  - 4. 一致性與標準
  - 5. 防錯機制
  - 6. 辨識重於回憶
  - 7. 彈性與使用效率
  - 8. 美感與簡約設計
  - 9. 協助辨識與從錯誤復原
  - 10. 說明文件與支援。
- **Slide 29: 破除迷思——「5 個人測試就能發現 85% 問題」是真的嗎？**
  - 數學模型真相：$ProblemsFound(n) = N(1 - (1 - \lambda)^n)$ ([[sources/sources_index#SRC-43|Nielsen & Landauer 1993]])。
  - 成立條件：單人發現率 $\lambda \approx 0.31$ 且使用者同質。
  - 失效邊界：複雜專業領域系統、高度異質客群、量化基準測試。
  - 真諦：不是只測 5 個人，而是「小規模、多輪迭代測試（Iterative Testing）」。

---

### 【第七章：總結與展望】
- **Slide 30: 核心解答——為什麼有些 App 特別好用？**
  - 金字塔整合模型：
    - 底層：穩固的心智模型與操作回饋（可理解）
    - 中層：精簡的資訊架構與高效率互動（低摩擦）
    - 頂層：尊重使用者自主權與長遠福祉的人本倫理（值得信賴）。
- **Slide 31: 初學者的設計行動心法**
  - 1. 你不是你的使用者（永遠以行為數據驗證直覺）。
  - 2. 減法勝過加法（好的設計是剛好給予所需的資訊）。
  - 3. 科技應服務人性，而非利用弱點（拒絕暗黑模式）。
- **Slide 32: 參考文獻與致謝 (References & Acknowledgements)**
  - 核心經典學術文獻與官方標準索引列表（ISO 9241, Norman, Sweller, Fitts, Hick, Nielsen, Brooke...）。
  - 感謝聆聽、重新閱讀按鈕。
