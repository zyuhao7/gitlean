# Day 25：cherry-pick

## 学习目标

把某个提交单独拿到当前分支。

## 核心概念

当某个修复在另一个分支上，但你只想拿这一笔提交，可以用 `cherry-pick`。

## 常用命令

```bash
git cherry-pick <commit-id>
```

## 今日练习

1. 在一个分支提交一个小修复。
2. 切换到另一个分支。
3. 找到修复提交的 commit id。
4. 执行 `git cherry-pick <commit-id>`。

## 检查点

你应该知道：cherry-pick 拿的是某个提交的改动，不是整个分支。

