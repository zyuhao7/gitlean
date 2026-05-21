# Git 1-5 天基础概念

这份笔记只覆盖入门阶段最常用的几个概念：Git 是什么、仓库怎么初始化、如何看状态、如何暂存、如何提交，以及怎么回看历史。

## 第 1 天：认识 Git

Git 是分布式版本控制系统，用来记录文件的变化历史。

你可以把它理解成：
- 每次提交都会保存一个版本快照
- 以后可以回看、比较、回退
- 多人协作时可以减少文件互相覆盖的问题

常见命令：

```bash
git --version
git help
```

## 第 2 天：初始化仓库

把一个普通文件夹变成 Git 仓库：

```bash
git init
```

执行后会生成 `.git` 目录，Git 会在这里保存版本信息。

常见检查命令：

```bash
git status
```

## 第 3 天：理解工作区和暂存区

Git 的基本流程通常是：

```text
工作区 -> 暂存区 -> 本地仓库
```

- 工作区：你正在编辑的文件
- 暂存区：准备提交的改动
- 本地仓库：已经提交保存的历史

把文件放入暂存区：

```bash
git add README.md
```

查看状态：

```bash
git status
```

## 第 4 天：第一次提交

提交就是把暂存区里的内容保存成一个历史版本：

```bash
git commit -m "add readme"
```

推荐养成的习惯：
- 提交信息写清楚做了什么
- 一个提交尽量只做一类事情
- 改动后先 `git add`，再 `git commit`

完整流程：

```bash
git add README.md
git commit -m "add readme"
```

## 第 5 天：查看历史记录

最常用的历史查看命令：

```bash
git log
git log --oneline
```

`git log --oneline` 更适合日常快速查看，会把每次提交压缩成一行。

示例输出：

```text
1a2b3c4 add readme
5d6e7f8 init project
```

### 1-5 天小结

学完这 5 天，你至少应该掌握：

- Git 是用来记录版本历史的
- `git init` 可以初始化仓库
- `git status` 可以看当前状态
- `git add` 可以把改动放进暂存区
- `git commit` 可以保存一次版本
- `git log` 可以查看历史提交

