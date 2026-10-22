# HA-list-01 · 链表（Hello 算法 · 数组与链表）

| 项 | 内容 |
|---|---|
| 上游文件 | resources/_vendor/hello-algo/codes/cpp/chapter_array_and_linkedlist/linked_list.cpp（commit `350f483`） |
| 服务任务 | 数据结构与算法 · 链表 |
| 顺序 | **先自己写，后看上游** |

## 自己实现

| 函数 | 要求 |
|---|---|
| `insert(n0, P)` | 在节点后插入，注意指针顺序 |
| `remove(n0)` | 删除后一节点，释放内存 |
| `access(head, index)` | 按索引访问，说明 O(n) |
| `find(head, target)` | 查找并返回索引 |

## 对照与差异（写完才填）

| 我的实现 | 上游 linked_list.cpp | 差异 | 我的结论 |
|---|---|---|---|
| | | | |

## 验收

- 能手画一次插入/删除前后的指针变化；
- 能解释为什么链表删除已知节点是 O(1)、按索引访问是 O(n)；
- 泄漏检查：`valgrind` 或 `-fsanitize=address` 无泄漏。
