# Day 18：修改最后一次提交

## 学习目标

使用 `amend` 修补最近一次提交。

## 核心概念

刚提交完才发现漏了文件、写错提交信息，可以用 `git commit --amend` 修改最后一次提交。

## 常用命令

```bash
git commit --amend
git commit --amend -m "better commit message"
```

## 今日练习

1. 提交一个文件。
2. 再修改一点内容。
3. 执行 `git add`。
4. 使用 `git commit --amend` 合并到上一次提交。

## 检查点

你应该知道：不要随便修改已经推送并被别人使用的公共提交。

