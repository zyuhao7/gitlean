# Day 29：排查问题

## 学习目标

用 Git 找到问题来源。

## 核心概念

Git 不只用来提交代码，也能帮助你追踪某行代码是谁改的、某个文件经历了哪些变化。

## 常用命令

```bash
git blame README.md
git show <commit-id>
git log -- README.md
```

## 命令说明

- `git blame`：查看每一行最后是谁改的。
- `git show`：查看某次提交的详细内容。
- `git log -- <file>`：查看某个文件的历史。

## 今日练习

1. 对 `README.md` 执行 `git blame`。
2. 找到一个 commit id。
3. 用 `git show` 查看它改了什么。

## 检查点

你应该知道：排查问题时，历史记录比猜测更可靠。

