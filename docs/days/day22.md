# Day 22：理解 HEAD

## 学习目标

知道 `HEAD` 指向哪里。

## 核心概念

`HEAD` 表示你当前所在的位置。通常它指向当前分支的最新提交。

## 常用命令

```bash
git log --oneline --decorate
```

你可能会看到：

```text
abc1234 (HEAD -> main, origin/main) update readme
```

## 今日练习

1. 查看当前 `HEAD`。
2. 切换到另一个分支。
3. 再次查看 `HEAD`。
4. 对比输出变化。

## 检查点

你应该知道：`HEAD` 不是分支本身，而是当前检出位置的指针。

