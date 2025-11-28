---
name: "Tech Debt / 技術負債"
about: 描述需要償還或重構的技術負債
title: "refactor: <簡短描述>"
labels: ["type:tech-debt", "status:triage"]
assignees: []
---

## 🧱 負債描述 (What & Where)
指出程式區域 / 模組 / 檔案。

## 🎯 造成的影響 (Impact)
 
- 維護成本：
- 缺陷風險：
- 可讀性 / 可測試性：

## 🔍 根因背景 (Background / Root Cause)
為何會形成（時程壓力 / 臨時 workaround / 缺少抽象）？

## 🛠 建議解法 (Proposed Remediation)
簡述做法（是否需 ADR）。

## ⏱ 預估成本 (Effort Estimation)
S / M / L 或 人日估算。

## 🧪 測試影響 (Test Impact)
是否需要補測試、冒煙測試或回歸測試？

## 📊 不修的後果 (If Not Addressed)
風險或未來成本。

## ✅ 驗收條件 (Acceptance Criteria)
 
- [ ] 完成重構並通過測試
- [ ] 移除不再需要的 code / 設定
- [ ] 更新相關文件

---
提交前自我檢查：

- [ ] 有具體影響說明
- [ ] 已提出建議解法或需要 spike
- [ ] 驗收條件可測試
