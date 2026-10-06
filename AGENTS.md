# AGENTS.md

- 所有的回應都使用繁體中文。
- 專案所使用的程式語言為 Python。
- 使用 conda 管理 Python 套件，環境名稱為 `iem_python`（如：`conda run -n iem_python python ...`）。
- Repo 目前仍接近 greenfield：僅有 `README.md`（`115-Programming`）與 Python 用 `.gitignore`（涵蓋 `__pycache__/`、`venv/`、`.venv/`、pytest/coverage 產物等），尚無 linter、formatter、test runner 設定。若新增工具，在此記錄經驗證過的確切指令。
- 完成前以 `git status --short` 確認，不提交生成物與環境產物。
