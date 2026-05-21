# Day 02：初始化仓库

## 学习目标

把一个普通文件夹变成 Git 仓库。

## 核心概念

Git 只会管理已经初始化的目录。初始化后，目录里会出现隐藏目录 `.git`，它保存了 Git 所需的版本信息。

## 常用命令

```bash
mkdir my-git-practice
cd my-git-practice
git init
git status
```

## 今日练习

1. 新建 `my-git-practice` 目录。
2. 在目录中执行 `git init`。
3. 执行 `git status` 查看仓库状态。

## 检查点

你应该知道：`.git` 目录是 Git 仓库的核心，不要随意删除。

