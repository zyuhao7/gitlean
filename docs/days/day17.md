# Day 17：取消暂存

## 学习目标

把已经 `git add` 的文件从暂存区拿回来。

## 核心概念

取消暂存不会删除你的修改，只是把文件从“准备提交”状态移回工作区。

## 常用命令

```bash
git restore --staged README.md
```

## 今日练习

1. 修改 `README.md`。
2. 执行 `git add README.md`。
3. 执行 `git status`。
4. 执行 `git restore --staged README.md`。
5. 再执行 `git status`。

## 检查点

你应该能区分：撤销修改和取消暂存是两件事。

