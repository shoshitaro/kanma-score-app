# GitHub Pages 公開コマンド

以下はターミナルで順番に実行する。

```bash
cd /Users/kotaro/Documents/Codex/2026-06-08/files-mentioned-by-the-user-20260608/outputs/github-pages-site

git add .
git commit -m "Initial GitHub Pages site"

gh repo create kanma-score-app --public --source=. --remote=origin --push
```

その後、GitHub のリポジトリ画面で以下を設定する。

1. `Settings`
2. `Pages`
3. `Build and deployment`
4. `Deploy from a branch`
5. Branch は `main`
6. Folder は `/ (root)`
7. `Save`

公開URLが発行されるまで数分待つ。
