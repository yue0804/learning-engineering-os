# MS-shell-03 · 版本控制（课程第 3 讲）

| 项 | 内容 |
|---|---|
| 上游文件 | resources/_vendor/missing-semester/_2020/version-control.md（commit `1d695c9`） |
| 前置 | MS-shell-02 |
| 建议用时 | 120 分钟 |
| 练习场 | 本仓库本身（learning-engineering-os） |

## 验收标准

1. 能画出 snapshot → tree → blob 的对象关系，并用 `git cat-file -p` 实证一次；
2. 建分支、制造一次冲突、解决，`git log --graph` 能讲清合并走向；
3. 撤销三件套各演示一次：`git restore --staged`、`git reset`、`git revert`，说明对历史的影响差别；
4. 说清 HEAD / 暂存区 / 工作区三者的关系。

## 必做动作

| 步 | 动作 | 留在哪 |
|---|---|---|
| 1 | `git cat-file -p HEAD` → tree → blob，记录三层输出 | records/ |
| 2 | 开分支改同一行，合并冲突，手工解决 | records/ |
| 3 | 三次撤销演示，各留一条前后对比 | records/ |
| 4 | 用 `git log --oneline --graph --all` 解释本仓库历史 | records/ |

## 与上游示例的差异

| 我的做法 | 上游做法 | 差异原因 |
|---|---|---|
| | | |
