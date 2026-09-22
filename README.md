# AI to Agent｜企業導入方法論

**AI to Agent Enterprise Operating Model**  
版本：**1.0.0**｜發布日期：**2026-09-22**｜語言：繁體中文

> 把人的工作，轉化成 AI 可以理解、判斷、執行、驗證，並全程受到人類治理的企業能力。

**AI Coach 益力康陳董 × CGM Coach 血糖教練｜2026 AI to Agent**

這是一套供企業工作設計、教學與導入試點使用的方法論文件及範本，不是可直接執行的 Agent 軟體，也不是國際標準或能力認證。設定任務規格之後，仍需要工具連接、權限設定與驗收。

## 先用一分鐘看懂

把 Agent 想成新進員工：能力再好，也需要知道工作目標、可用資料、能做的決定，以及完成標準。

**VAD 看懂工作 → VAC 定義工作 → DC 管住決策。**

| 記憶點 | 固定內容 | 用途 |
|---|---|---|
| 6 個工作環節 | Goal → Context → Reason → Decide → Action → Evaluate | 描述工作如何完成與驗證 |
| 3 個設計工具 | VAD、VAC、DC | 把企業工作轉為可交接規格 |
| 4 級自主權 | A1 輔助、A2 核准、A3 任務自主、A4 流程自主 | 設定授權範圍 |
| 1 個治理邊界 | Human Governance | 全程管理權限、責任、資料及稽核 |

**6・3・4・1 是本專案的教學記憶法，不是分數或計算公式。** 多 Agent 協作不是自主權等級；單一或多個 Agent 都必須遵守授權。

## 五分鐘開始

1. 選一項範圍清楚、可驗收的企業工作。
2. 用 [VAD 範本](templates/VAD.md) 畫出人、資料、判斷、工具與例外。
3. 用 [VAC 範本](templates/VAC.md) 填寫目標、上下文、行動、驗收標準。
4. 用 [DC 範本](templates/DC.md) 設定判斷條件、A1–A4、自主權及停止條件，並讓 VAC 引用 DC 的版本。
5. 先以模擬或唯讀方式驗證，再依核准的範圍啟用執行權限。

完整示例：[會議紀錄轉行動任務](examples/meeting-to-action.md)。

## 閱讀導覽

| 文件 | 內容 |
|---|---|
| [方法論完整說明](docs/METHODOLOGY.md) | 定義、架構、閉環、治理與 Promptless |
| [費曼學習版](docs/FEYNMAN_GUIDE.md) | 用新進員工比喻解釋導入方法 |
| [名詞與邊界](docs/GLOSSARY.md) | 中英文唯一用語與技術定位 |
| [一致性審查](docs/CONSISTENCY_REVIEW.md) | 舊版問題、修正理由與檢查結果 |
| [導入與驗收](docs/IMPLEMENTATION.md) | 從工作選擇到驗收、改善 |
| [技術案例維護](docs/TECHNOLOGY_NOTES.md) | 如何更新 Jev、LLM、MCP 等案例 |
| [GitHub 上傳指南](docs/GITHUB_GUIDE.md) | 建立倉庫、上傳與版本發布 |
| [版本紀錄](CHANGELOG.md) | 本版內容與後續版本規則 |
| [引用資訊](CITATION.cff) | 作者、版本與發布日期 |
| [版權與授權](LICENSE) | 保留權利聲明 |
| [貢獻規則](CONTRIBUTING.md) | 修正建議與內容維護 |

## 版權與引用

AI Coach 益力康陳董 × CGM Coach 血糖教練｜2026 AI to Agent

Copyright © 2026 陳俊宏。All rights reserved.

本版未授予 MIT、Apache 或 Creative Commons 等開放授權。公開展示不等於授予任意商用、改作或再散布權；使用條件見 [LICENSE](LICENSE)。這是保留權利的文件專案，不宣稱為開源專案。

建議引用：陳俊宏（2026）。《AI to Agent Enterprise Operating Model：企業導入方法論》（1.0.0 版）。