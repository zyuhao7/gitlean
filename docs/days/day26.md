# Day 26：Pull Request 工作流

## 学习目标

理解团队如何通过 Pull Request 审核和合并代码。

## 核心概念

Pull Request 是把分支改动提交给团队评审的流程。它通常包含代码差异、讨论、自动检查和合并记录。

## 常见流程

```text
更新 main -> 创建 feature 分支 -> 提交代码 -> 推送分支 -> 创建 Pull Request -> 审核 -> 合并
```

## 常用命令

```bash
git switch main
git pull
git switch -c feature/demo
git push -u origin feature/demo
```

## 今日练习

1. 从最新 `main` 创建分支。
2. 提交一次修改。
3. 推送分支。
4. 在网页上创建 Pull Request。

## 检查点

你应该知道：PR 的重点不是形式，而是让改动可审查、可讨论、可追踪。

