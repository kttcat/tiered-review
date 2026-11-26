# 分級審查制

English 版本請見 [README.md](README.md)。

給 AI agent 的三級審查框架。

- **第一級：事前批**——對外、不可逆、牽涉金錢或授權、改定案，動手前必須拿到負責人原話批准。
- **第二級：事後看**——唯讀整理、可逆整理、草稿，先做、做完報告。
- **第三級：只記 log**——例行檢查，不打擾。

判斷規則：不可逆、對外、牽涉他人的資料或權益、或分不清是哪一級，任一成立就升第一級。

完整內容：[分級審查制.md](分級審查制.md) · [tiered-review.md](tiered-review.md) (English)

## 相關專案

同一套流程的三個部分——規範、分級、留痕：

- [workflow-skills](https://github.com/kttcat/workflow-skills) — 規範：九支學回來的工作流程 skills。
- [tiered-review](https://github.com/kttcat/tiered-review) — 分級：這個 repo。
- [sqlite-audit-log](https://github.com/kttcat/sqlite-audit-log) — 留痕：只追加的 SQLite 稽核紀錄。

## 授權

MIT — 見 [LICENSE](LICENSE)。
