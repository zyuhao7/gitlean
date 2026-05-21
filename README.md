# Git Learn in 30 Days

这是一个面向初学者的 Git 30 天学习路线。

目标不是背命令，而是通过每天一个小场景，理解 Git 怎么记录代码变化、怎么协作、怎么回退、怎么解决冲突。

## 适合谁

- 刚开始学 Git 的同学
- 会用 `git add`、`git commit`，但不理解分支、冲突、rebase 的同学
- 想把 Git 用在真实项目协作中的同学

## 学习方式

每天建议花 30 到 60 分钟：

1. 先看当天概念
2. 再跟着命令操作
3. 最后完成当天练习

主教程在这里：

[30 天 Git 学习路线](docs/git-30-days.md)

## 学习路线图

```mermaid
flowchart LR
    A["第 1-5 天<br/>基础概念"] --> B["第 6-10 天<br/>分支与合并"]
    B --> C["第 11-15 天<br/>远程仓库协作"]
    C --> D["第 16-20 天<br/>撤销与修复"]
    D --> E["第 21-25 天<br/>进阶工作流"]
    E --> F["第 26-30 天<br/>实战与总结"]
```

## 最小准备

安装 Git 后，先配置你的身份：

```bash
git config --global user.name "你的名字"
git config --global user.email "你的邮箱"
```

检查是否配置成功：

```bash
git config --global --list
```

## 推荐练习仓库结构

```text
my-git-practice/
  README.md
  notes/
    day01.md
    day02.md
  src/
    hello.txt
```

你可以每天在这个练习仓库里提交一次，30 天结束后会得到一条完整的 Git 学习提交记录。
