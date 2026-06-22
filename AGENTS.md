# AGENTS.md

給所有 AI agent 的跨工具指引。本檔為通用慣例（多數工具會自動讀取）；Cursor 另有 `.cursor/rules/` 會自動套用，內容與本檔一致。

## 專案簡介

AGI（Agentic Guideline Intelligence）是一套由上百份品牌 Brand Guideline 蒸餾出的知識圖譜 + Skills。主要能力都集中在 `.agents/skills/agi/`：

- 主 skill 與三種模式：`.agents/skills/agi/SKILL.md`
- 知識庫與維護原理：[`MAINTENANCE.md`](MAINTENANCE.md)
- 一般使用方式：[`README.md`](README.md)

## 中文用語規範（必守）

撰寫、修改、產出 **任何中文內容** 時（含回覆、註解、commit message、Markdown、YAML、Skill 說明等），須使用 **台灣繁體正體** 的常見說法，避免大陸簡體用語、大陸慣用詞或不符合台灣語感的寫法。寫完後用台灣讀者的角度看一遍，不順就修到順為止。

基本原則：

- 使用繁體正體字，不用簡體字
- 優先採台灣常見詞彙與語序
- 專有名詞若業界在台灣有慣用譯法，以台灣慣用為準
- 不確定時，選台灣媒體、政府公文、本土品牌常見的說法

用語對照表（單一事實來源）：[`.agents/taiwan-traditional-chinese.lexicon.yaml`](.agents/taiwan-traditional-chinese.lexicon.yaml)

- 產出或修改中文前，若對照表尚未在 context 中，須先以 Read 工具讀取
- 依 lexicon 的「避免 → 建議」對照替換用語
- 對照表未列出的詞，仍以台灣繁體正體語感判斷，勿引入中國（俗稱：大陸）慣用詞或支語
