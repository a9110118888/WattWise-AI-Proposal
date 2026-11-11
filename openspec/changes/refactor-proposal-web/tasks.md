# Tasks

## 1. 系統架構與規格定義 (System Architecture & Specs)

- [x] 1.1 建立根目錄 `DESIGN.md`，定義 FR-01 至 FR-05、八大模組 Mermaid 圖、決策流程圖、具行號 01-25 虛擬碼與無虛構數據之評估計畫，並驗證檔案完整生成
- [x] 1.2 建立 `openspec/specs/wattwise-agent/spec.md` 與 Delta Spec，使用 SHALL 與 Given/When/Then 語法規範八大模組與安全守門機制，並驗證 OpenSpec 格式無誤
- [x] 1.3 建立 `openspec/changes/refactor-proposal-web/` 工作流工件 (`proposal.md`, `design.md`, `tasks.md`)，並通過 `openspec validate` 驗證

## 2. 提案報告書重構 (Proposal Report Refactor)

- [x] 2.1 建立 `docs/Proposal_Refactored.md` 之 Abstract 區塊，完成 A to F 六段式結構 (Attention, But, Cure, Development, Experiments, Findings) 與 500 字專業摘要
- [x] 2.2 撰寫 Deep Research 核心內容：5 Cores 領域思維、3 Trade-offs 專業爭論對照表、10 Details 深度問答與邊界設計，並確認覆蓋電力與熱力學面向
- [x] 2.3 撰寫 Introduction Refactor，整合 A2Z Outline (A-F 與 G-L：General, However, In Literature, Judgement SWOT, Keypoint, List)，引用 2025-2026 最新電價與能耗客觀數據
- [x] 2.4 撰寫 Related Work Refactor，涵蓋 1/2 AI 技術與 1/2 領域電力工程，建立包含 5 篇 2024-2026 學術論文之 Article Summary Table，並收斂出 Research Gap

## 3. 展示與互動模擬網站建置 (Interactive Web Application)

- [x] 3.1 建立根目錄 `index.html` 之科技深色介面骨架與導覽列，導入 Tailwind CSS、Mermaid.js、Chart.js 與 FontAwesome 圖示庫
- [x] 3.2 實作 Abstract A-F 卡片區與 A4 橫式高密度 NUMBERING 資訊圖表視覺化專區 (Bento Grid 呈現 01-26 編號映射)
- [x] 3.3 實作 Introduction (A-F/G-L)、SWOT 矩陣與 Related Work 文獻比較表展示元件
- [x] 3.4 實作 Deep Research 互動切換區 (Tab 切換 5 Cores、3 Trade-offs、10 Details 互動手風琴)
- [x] 3.5 實作 OpenSpec 規格與 DESIGN.md 架構視覺化區 (Mermaid 圖表自動渲染與 01-25 行號虛擬碼高亮展示)
- [x] 3.6 實作 WattWise AI 互動模擬器，支援三個核心情境切換、ReAct 思考歷程展示、白名單 Function Calling 狀態、Chart.js 24 小時負載曲線與過載安全守門警報

## 4. 專案文件與交付驗證 (Project Documentation & Verification)

- [x] 4.1 建立根目錄 `README.md`，說明專案架構、OpenSpec 工作流程、提案規範符合度對照表與線上預覽指引
- [x] 4.2 執行靜態語意檢查與 OpenSpec CLI 驗證，確認無死鏈結並確保純客戶端運行相容性

