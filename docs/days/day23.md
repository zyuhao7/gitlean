# Day 23：rebase 入门

## 学习目标

理解 `rebase` 的用途。

## 核心概念

`merge` 像是把两条线汇合，`rebase` 像是把你的提交挪到最新主线后面。

## 常用命令

```bash
git switch feature/demo
git rebase main
```

## 使用建议

- 本地个人分支可以用 rebase 整理历史。
- 公共分支不要随意 rebase。
- rebase 发生冲突时，需要解决后继续。

```bash
git rebase --continue
```

## 今日练习

1. 创建一个 feature 分支。
2. 在 main 分支新增一次提交。
3. 回到 feature 分支执行 `git rebase main`。

## 检查点

你应该知道：rebase 会改写提交位置，使用前要确认影响范围。

