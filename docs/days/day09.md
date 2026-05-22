# Day 09：切换分支

## 学习目标

熟练使用 `git switch`，并理解老命令 `git checkout` 为什么还会经常出现。

## 核心概念

切换分支会让工作区变成目标分支对应的文件状态。

现在推荐新手优先使用 `git switch`，因为它只负责切换分支，语义更清楚。

很多旧教程还会使用 `git checkout`。它是老命令，既能切换分支，也能恢复文件，所以刚学 Git 时容易混淆。

## 常用命令

```bash
git switch main
git switch feature/notes
git switch -c feature/readme
```

对应的 `checkout` 写法：

```bash
git checkout main
git checkout feature/notes
git checkout -b feature/readme
```

可以这样记：

- `git switch <branch>`：切换到已有分支
- `git switch -c <branch>`：创建并切换到新分支
- `git checkout <branch>`：老写法，作用类似切换分支
- `git checkout -b <branch>`：老写法，作用类似创建并切换分支

日常学习建议：

- 新项目和新教程优先用 `git switch`
- 看旧文章或旧项目脚本时，看到 `checkout` 知道它可能是在切换分支

## 今日练习

1. 在 `feature/notes` 分支创建一个文件并提交。
2. 切回 `main`。
3. 观察文件是否还在。
4. 再切回 `feature/notes` 对比变化。
5. 用 `git checkout main` 试一次老写法，再用 `git switch feature/notes` 切回来。

## 检查点

你应该知道：不同分支可以拥有不同的文件内容和提交历史；`checkout` 是老写法，`switch` 是更清晰的新写法。
