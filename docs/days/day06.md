# Day 06：查看具体修改

## 学习目标

知道文件到底改了什么。

## 核心概念

`git status` 告诉你哪些文件变了，`git diff` 告诉你具体变了哪些行。

## 常用命令

```bash
git diff
git diff --staged
```

- `git diff`：查看工作区中还没暂存的修改。
- `git diff --staged`：查看已经暂存、还没提交的修改。

## 今日练习

1. 修改 `README.md`。
2. 执行 `git diff`。
3. 执行 `git add README.md`。
4. 执行 `git diff --staged`。

## 检查点

你应该能在提交前检查自己到底准备提交了什么。

