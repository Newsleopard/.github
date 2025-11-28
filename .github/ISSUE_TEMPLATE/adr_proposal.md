---
name: "ADR Proposal / 架構決策提案"
about: 提出需要討論與記錄的架構決策
title: "adr: [Platform/Service] <決策主題>"
labels: ["type:adr", "status:triage"]
assignees: []
---

## 🎯 決策主題 (Decision Topic)

**ADR 類型**: [ ] Platform ADR (影響多個微服務)  [ ] Service ADR (單一儲存庫)

**如果是 Service ADR，請指定 GitHub 儲存庫名稱**: _______________
(例如：nlm-contacts, backend-v2, java-library-commons, nlInc-vpnMgmtTools)

## 🔍 背景 (Context)

為什麼現在需要做這個決策？

描述驱動這個決策的背景、問題或需求：

- 觸發事件或問題
- 業務或技術需求
- 現有方案的限制

## 💡 建議方案 (Proposed Decision)

我們建議採用什麼解決方案？

明確描述建議的方案，要具體可操作：

- 具體的技術選擇
- 實施的關鍵要點
- 重要的設計原則

## ⚖️ 替代方案 (Alternatives Considered)

我們還考慮了哪些選項？為什麼沒有選擇？

- **選項 A**: 簡述 + 為什麼沒選
- **選項 B**: 簡述 + 為什麼沒選

## 💥 影響 (Consequences)

這個決策會帶來什麼影響？

### 正面影響

- 解決了什麼問題
- 帶來什麼好處
- 提升了什麼能力

### 負面影響/風險

- 需要承擔什麼代價
- 可能帶來的風險
- 需要額外的工作

### 後續行動

- [ ] 需要完成的具體任務
- [ ] 需要更新的文檔或配置
- [ ] 需要通知的相關團隊

## 🔗 關聯 (Links)

相關 Issue / PR：

## 👥 需要參與的角色 (Stakeholders)

**Platform ADR**: 所有團隊成員

**Service ADR**: Backend / Frontend / DevOps / Data / Security / Product（刪除不適用）

**相關儲存庫團隊**: _______________

## ⏱ 時間敏感度 (Time Criticality)

是否有截止時間 / 對 Roadmap 影響？

## 🚫 不在範圍 (Out of Scope)

避免討論發散。

---
提交前自我檢查：

- [ ] 背景與觸發清楚
- [ ] 有 2+ 合理選項
- [ ] 已列出需參與角色
- [ ] 已確認 ADR 類型 (Platform vs Service)
- [ ] 如果是 Service ADR，已指定 GitHub 儲存庫名稱
- [ ] 已添加適當標籤：`platform` 或 `service:{repository-name}`
