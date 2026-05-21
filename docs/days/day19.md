# Day 19：回退提交

## 学习目标

理解 `revert` 和 `reset` 的区别。

## 核心概念

`revert` 会新增一个提交，用来抵消旧提交的影响，历史仍然完整。

`reset` 会移动分支指针，可能改写历史。多人协作时要谨慎使用。

## 常用命令

```bash
git revert <commit-id>
git reset --soft HEAD~1
git reset --hard HEAD~1
```

新手优先使用：

```bash
git revert <commit-id>
```

## 今日练习

1. 新增一个错误提交。
2. 用 `git log --oneline` 找到 commit id。
3. 用 `git revert` 撤销它。

## 检查点

你应该知道：公共分支上优先使用 `revert`，少用会改写历史的 `reset`。

