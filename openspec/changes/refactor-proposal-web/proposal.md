# Proposal

## Why

台灣現行智慧建築與住宅能源管理面臨台電新版時間電價價差擴大（3.5 至 4 倍）、既有智慧電表遙測與用戶感知存在語意鴻溝，以及通用生成式 AI 缺乏電氣工程物理限制與安全防護之三重瓶頸。為建立兼具高診斷可解釋性、電氣安全守門與電價經濟效益之系統，亟需導入 OpenSpec 規格驅動開發，將 WattWise AI 的八大模組架構、白名單工具呼叫機制、信心度澄清迴圈與實時過載保護轉化為嚴謹的工程規範與互動可視化平台。

## What Changes

- 新增 `wattwise-agent` 核心系統能力規格，定義八大模組協同機制與安全約束。
- 新增白名單 Function Calling 限制與低信心度 (< 0.80) 主動追問澄清規範。
- 新增實時用電負載過載安全防護圍欄（Safety Guard）與主動階梯降級機制。
- 重構專題提案報告書 `docs/Proposal_Refactored.md`，納入 A to F 六段式 Abstract、5 Cores、3 Trade-offs、10 Details、SWOT 分析與 5 篇 2024–2026 文獻綜述。
- 建立免伺服器端（Serverless）深色科技風格之 GitHub Pages 展示與互動模擬網站 `index.html`。

## Capabilities

### New Capabilities
- `wattwise-agent`: 定義 WattWise AI 之八大模組協作、白名單工具調用、信心度澄清迴圈、過載安全守門及建築熱力學舒適度約束等系統行為規範。

### Modified Capabilities
（無修改既有 Capabilities，本變更為初始建立之系統核心能力）

## Impact

- 影響系統整體架構與推理代理執行邏輯，所有外部呼叫均受限於白名單安全分派器。
- 提供前端互動模擬器運行所需的情境數據結構、ReAct 思考鏈可視化格式與安全攔截日誌介面。

