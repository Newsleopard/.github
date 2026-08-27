Tier: 1 — <一句話：為什麼是這個 tier（0=docs/註解/非邏輯 config 或 ≤30 LOC 無控制流；1=一般改動；2=auth/secrets、DB schema/migration、破壞性 infra、跨服務 contract）>
Pre-PR self-review: not run (no-review-tool); codex-verify: skipped (no trigger)
Non-blocking budget: round 1

<!--
⚠️ 上面三行是宣告行 —— 機器（poller / pr-converge）與 reviewer 都會讀，請保留在 PR body 最上方並照實填寫：
- `Tier:` 必須錨在行首，格式 `Tier: 0|1|2 — 理由`；拿不準往上判。
- `Pre-PR self-review:` 為封閉詞彙（正典：nlm-system-overview docs/prd/2026-08-08-pre-pr-tiered-self-review-prd.md §3.3）。
  預填值是「機器上沒有自審工具」的誠實預設；有跑過就照實改，例如 `@critic ×1; codex-verify: skipped (no trigger)`。
- `Non-blocking budget:` 預設 `round 1` ＝ 每位 reviewer 的非阻塞意見在本 PR 修一輪、之後開 follow-up issue。
  作者要每輪都收可改成 `all rounds — <理由>`。⚠️ 本說明區塊必須留在宣告行「之後」（parser 取第一個命中）。
-->

## 🧩 變更類型 (Change Type)

- [ ] ✨ Feature (新功能)
- [ ] 🐛 Bugfix (修復錯誤)
- [ ] 💄 Code style update (格式化、變數命名，無邏輯變動)
- [ ] ♻️ Refactoring (重構，無功能變動)
- [ ] 👷 CI / CD changes
- [ ] 📝 Documentation changes
- [ ] 🧪 Tests (新增或修改測試)
- [ ] 📦 Dependency update (套件更新)

## 📝 變更內容 (Change Summary)

請簡述變更的內容與原因。

## 🧪 如何驗證 (How to Test)

請列出驗證此變更的步驟：

1.
2.

## 🔗 關聯 (Links)

- Issue: #
- ADR:
- Design Doc:

## ✅ 檢查清單 (Checklist)

- [ ] 我已執行過 `Self-Review`，確認程式碼邏輯清晰
- [ ] 我已確認沒有引入 **Breaking Change** (若有，請在 Summary 說明)
- [ ] 我已新增/更新對應的 **Unit Test** 或 **E2E Test**
- [ ] 我已執行 `lint` 與 `test` 並確認通過
- [ ] (若適用) 我已更新對應的文件 (API docs, README)
