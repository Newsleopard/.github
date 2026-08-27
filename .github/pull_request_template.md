Tier: <0|1|2> — <一句話理由>
Pre-PR self-review: <first-axis>; codex-verify: <codex-state>
Non-blocking budget: round 1

<!--
⚠️ 上面三行是宣告行，請保留在 PR body 最上方並照實填寫：
- `Tier` 那一行：請把 <0|1|2> 換成一個數字、錨在行首（機器會讀這行）。⚠️ 留著 placeholder 不是
  「回到預設」—— /pr-converge 會 fail-closed 直接 ESCALATED、poller 也拿不到 cheap lane，一定要換成數字。
  0＝docs/註解/非邏輯 config 或 ≤30 LOC 無控制流（⚠️ 例外：PRD / ADR / Spec / Implementation Plan
  文件永遠至少 Tier 1）；1＝一般改動；2＝auth/secrets、DB schema/migration、
  破壞性 infra、跨服務 contract。拿不準往上判。宣告 Tier 0 時保留 `Tier` 那行（填 0）、
  刪掉下面兩行（Tier 0 沒有自審／額度宣告行）。
- `Pre-PR self-review` 那一行（給 reviewer 讀）是封閉詞彙，見團隊規則〈宣告行〉一節。請照實換值：
  有自審工具就先跑完自審再填（例：`@critic ×1; codex-verify: skipped (no trigger)`）；機器上
  沒有自審工具才填 `not run (no-review-tool); codex-verify: skipped (no trigger)`；宣告 Tier 2 時
  值也要跟著換。留著 placeholder ＝ 明顯沒填，reviewer 會退回。
- `Non-blocking budget` 那一行（機器會讀）預設 `round 1` ＝ 每位 reviewer 的非阻塞意見在本 PR
  修一輪、之後開 follow-up issue 追。作者要每輪都收可改成 `all rounds — <理由>`。
  本說明區塊必須留在宣告行「之後」（parser 取第一個命中）。
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

- [ ] 最上方的 `Pre-PR self-review` 宣告行已照實填寫（自審狀態以那行為準）
- [ ] 我已確認沒有引入 **Breaking Change** (若有，請在 Summary 說明)
- [ ] 我已新增/更新對應的 **Unit Test** 或 **E2E Test**
- [ ] 我已執行 `lint` 與 `test` 並確認通過
- [ ] (若適用) 我已更新對應的文件 (API docs, README)
