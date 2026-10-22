# MS-shell-04 · 调试与性能分析（课程第 4 讲）

| 项 | 内容 |
|---|---|
| 上游文件 | resources/_vendor/missing-semester/_2020/debugging-profiling.md（commit `1d695c9`） |
| 前置 | MS-shell-03 |
| 建议用时 | 120 分钟 |

## 验收标准

1. 用 `printf` + 日志分级定位一个真实 bug，留下「假设 → 验证」过程；
2. 用调试器（gdb 或 pdb）设断点、单步、看调用栈，抓到一次越界或空指针；
3. 用 `time` 加性能工具（`perf` / `valgrind` / `cProfile`）指出一段代码的时间去向；
4. 用 `strace` 或 `ltrace` 观察一次系统调用。

## 必做动作

| 步 | 动作 | 留在哪 |
|---|---|---|
| 1 | 写一个会崩溃的小程序（越界），先用 printf 猜，再用 gdb 定行号 | work/ms-2020-shell-04/ |
| 2 | 记录 gdb 的 `bt`、`frame`、`print` 输出 | records/ |
| 3 | 对同一段循环用 `time` 与剖析工具对比，写下瓶颈 | records/ |
| 4 | `strace -c` 一次，解释占比最高的调用 | records/ |

## 环境说明

Windows 下 gdb 需 MinGW/LLVM 工具链；若本机没有，先在 WSL 或 VS Code 调试器里完成同等动作，并在记录里写明环境差异。
