# Day 10：合并分支

## 学习目标

把分支上的成果合并回主分支。

## 核心概念

合并就是把一条分支上的提交带到另一条分支。

## 常用命令

```bash
git switch main
git merge feature/notes
```

## 今日练习

1. 在 `feature/notes` 分支提交一个文件。
2. 切回 `main`。
3. 执行 `git merge feature/notes`。
4. 查看文件是否出现在 `main`。

## 检查点

你应该知道：合并前要确认当前所在分支，避免把方向弄反。

