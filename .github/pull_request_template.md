Tier: <0|1|2> — <一句話理由>
Pre-PR self-review: not run (no-review-tool); codex-verify: skipped (no trigger)
Non-blocking budget: round 1

<!--
⚠️ 上面三行是宣告行，請保留在 PR body 最上方並照實填寫：
- `Tier:` 請把 <0|1|2> 換成一個數字、錨在行首（機器會讀這行；留著 placeholder 視同未宣告）。
  0＝docs/註解/非邏輯 config 或 ≤30 LOC 無控制流；1＝一般改動；2＝auth/secrets、DB schema/migration、
  破壞性 infra、跨服務 contract。拿不準往上判。宣告 Tier 0 時請把下面兩行刪掉（Tier 0 沒有宣告行）。
- `Pre-PR self-review:`（給 reviewer 讀）是封閉詞彙，見團隊規則〈宣告行〉一節。預填值只適用
  「機器上沒有自審工具」的情況 —— 有工具請先跑完自審再開 PR、照實改寫
  （例：`@critic ×1; codex-verify: skipped (no trigger)`）；宣告 Tier 2 時這行也要跟著換值。
- `Non-blocking budget:`（機器會讀）預設 `round 1` ＝ 每位 reviewer 的非阻塞意見在本 PR 修一輪、
  之後開 follow-up issue 追。作者要每輪都收可改成 `all rounds — <理由>`。
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

- [ ] 我已執行過 `Self-Review`，確認程式碼邏輯清晰
- [ ] 我已確認沒有引入 **Breaking Change** (若有，請在 Summary 說明)
- [ ] 我已新增/更新對應的 **Unit Test** 或 **E2E Test**
- [ ] 我已執行 `lint` 與 `test` 並確認通過
- [ ] (若適用) 我已更新對應的文件 (API docs, README)
