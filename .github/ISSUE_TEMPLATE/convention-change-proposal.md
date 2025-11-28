---
name: "Convention Change Proposal"
about: 提出一項規範（新增 / 修改 / 移除）的具體提案
title: "convention: <簡短描述>"
labels: ["change-medium", "status:triage"]
assignees: []
---

# Convention Change Proposal

## 摘要 (One-liner)

簡述你要改變什麼，以及核心動機。

## 變更類型

- [ ] L1 低 (拼字 / 排版 / 格式)
- [ ] L2 一般 (補充內容 / 非破壞新增)
- [ ] L3 跨層 (API / 事件 / 架構邊界)
- [ ] L4 策略 (方向、棄用、重大調整)

## 背景 / 動機

為什麼需要這個變更？目前的問題或痛點是？

## 建議內容 (Proposed Change)

說明具體調整：新增段落、刪除章節、替換語句、結構重排…

## 選項對比 (可選)

| 選項 | 優點 | 缺點 | 評估 |
|------|------|------|------|
| 方案 A |  |  |  |
| 方案 B |  |  |  |

## 影響評估

- 涉及檔案 / 章節：
- 是否影響前後端協作？(Y/N 說明)
- 是否需要更新 Glossary？(Y/N 說明)
- 對現有程式碼是否造成破壞？

## 推薦決策

最終推薦方案與主要理由。

## Rollout / 落地建議

- 是否需要 `provisional` 暫行（Provisional）？（若為試行列出觀察指標）
- 是否需要自動化支持（lint / script）？

## 風險與緩解

| 風險 | 徵兆 | 緩解 |
|------|------|------|
|  |  |  |

## 待辦 (Merge 前)

- [ ] 已通知相關 Owner
- [ ] 已檢視變更級別符合 Label
- [ ] 無敏感資料

## 後續 (Merge 後)

- [ ] 更新 `CHANGELOG`
- [ ] （若 `provisional` 暫行（Provisional））建立 Follow-up Issue：到期日 YYYY-MM-DD

/label <請調整對應的最終 label>
