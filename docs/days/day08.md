# Day 08：创建分支

## 学习目标

理解分支是什么，并创建第一个分支。

## 核心概念

分支是一条独立的开发线。你可以在分支上开发新功能，不影响主分支。

## 常用命令

```bash
git branch
git branch feature/notes
git switch feature/notes
```

也可以一步创建并切换：

```bash
git switch -c feature/notes
```

## 今日练习

1. 创建 `feature/notes` 分支。
2. 切换到这个分支。
3. 新增 `notes/branch.md` 并提交。

## 检查点

你应该能说清楚：分支让不同工作可以并行进行。

