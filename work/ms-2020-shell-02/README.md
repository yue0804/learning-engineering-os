# MS-shell-02 · Shell 工具与脚本（课程第 2 讲）

| 项 | 内容 |
|---|---|
| 上游文件 | resources/_vendor/missing-semester/_2020/shell-tools.md（commit `1d695c9`） |
| 前置 | MS-shell-01 |
| 建议用时 | 90–120 分钟 |

## 验收标准

1. 写出一个带 shebang 的脚本：变量、`if`、`for`、函数各用到一次，且 `set -e` 生效（故意制造失败验证）；
2. 用 `find` 完成 5 类检索：按名、按时间、按大小、按类型、组合条件；
3. 用 `grep` / `sed` 从一份真实日志里提取并格式化目标行；
4. 用 `history` 与 `Ctrl-R` 找回一条旧命令。

## 必做动作

| 步 | 动作 | 留在哪 |
|---|---|---|
| 1 | `script.sh`：统计目录下 .txt 文件数与总行数 | work/ms-2020-shell-02/ |
| 2 | `find` 五个用例，每个一行命令 + 一行解释 | records/ |
| 3 | 造 200 行假日志，用 `grep -c`、`sed -n` 取区间 | records/ |
| 4 | glob 练习：`*.{py,sh}`、`**/*.txt` 与 `nullglob` 行为差异 | records/ |

## 与上游示例的差异

| 我的做法 | 上游做法 | 差异原因 |
|---|---|---|
| | | |
