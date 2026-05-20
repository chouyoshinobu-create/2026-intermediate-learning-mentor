# 2026中級學習導師專案

這個專案使用 Git 同步，建議 Air 和學校的 MacBook Pro 都各自放一份本機 repo：

- Air：`/Users/yoshi/Projects/2026中級學習導師專案`
- Pro：`/Users/yoshi/Projects/2026中級學習導師專案`

## 日常同步流程

開始工作前：

```bash
git pull
```

工作告一段落：

```bash
git status
git add .
git commit -m "Update project"
git push
```

## 原則

- 專案本體放在本機 `~/Projects`，不要放 OneDrive。
- GitHub/GitLab 負責同步兩台電腦。
- OneDrive 可放教材素材、輸出成品、備份文件，但不放正在開發的 repo。
- `.env`、密鑰、快取、依賴資料夾不要提交。
