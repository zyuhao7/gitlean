# Day 12：连接远程仓库

## 学习目标

理解远程仓库，并把本地仓库关联到 GitHub 或 Gitee。

## 核心概念

远程仓库是团队共享代码的位置。本地提交只有推送后，别人才能在远程看到。

## 常用命令

```bash
git remote -v
git remote add origin https://github.com/your-name/your-repo.git
```

## 今日练习

1. 在 GitHub 创建一个空仓库。
2. 在本地执行 `git remote add origin <url>`。
3. 执行 `git remote -v` 检查地址。

## 检查点

你应该知道：`origin` 通常是默认远程仓库的名字。

