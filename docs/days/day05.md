# Day 05：查看历史记录

## 学习目标

学会查看提交历史。

## 核心概念

Git 会按时间保存提交记录。每条提交都有一个提交编号，也叫 commit id。

## 常用命令

```bash
git log
git log --oneline
```

`git log --oneline` 更适合日常快速查看：

```text
1a2b3c4 add readme
5d6e7f8 init project
```

## 今日练习

1. 修改 `README.md`。
2. 再提交一次。
3. 执行 `git log --oneline`。

## 检查点

你应该能从历史里看出每次提交的顺序和提交信息。

