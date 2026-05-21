# Day 20：临时保存修改

## 学习目标

使用 `git stash` 临时保存还不能提交的修改。

## 核心概念

当你正在写一半，需要先切换分支处理别的事，可以把当前修改临时收起来。

## 常用命令

```bash
git stash
git stash list
git stash pop
```

## 今日练习

1. 修改一个文件但不提交。
2. 执行 `git stash`。
3. 执行 `git status`。
4. 执行 `git stash pop` 恢复修改。

## 检查点

你应该知道：stash 适合临时保存，不适合长期存放重要工作。

