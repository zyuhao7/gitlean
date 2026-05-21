# Day 04：第一次提交

## 学习目标

完成第一次 `commit`，理解提交就是保存一个版本快照。

## 核心概念

提交会把暂存区中的内容保存到本地仓库。每次提交都应该描述这次改动做了什么。

## 常用命令

```bash
git add README.md
git commit -m "add readme"
```

## 提交信息建议

好的提交信息：

```text
add readme
fix typo in readme
docs: add git notes
```

不推荐：

```text
update
test
111
```

## 今日练习

1. 暂存 `README.md`。
2. 提交一次。
3. 提交信息写清楚做了什么。

## 检查点

你应该知道：只有 `git commit` 后，改动才真正进入版本历史。

