# HA-array-01 · 数组（Hello 算法 · 数组与链表）

| 项 | 内容 |
|---|---|
| 上游文件 | resources/_vendor/hello-algo/codes/cpp/chapter_array_and_linkedlist/array.cpp（commit `350f483`） |
| 服务任务 | 数据结构与算法 · 数组 |
| 顺序 | **先自己写，后看上游**；看之前不得打开 array.cpp |

## 自己在不看上游的前提下实现

| 函数 | 要求 |
|---|---|
| `randomAccess(nums, size)` | 随机访问一个元素，说明 O(1) 的由来 |
| `extend(nums, size, enlarge)` | 扩容并拷贝，说明为何是 O(n) |
| `insert(nums, size, num, index)` | 指定位置插入，注意越界检查 |
| `remove(nums, size, index)` | 指定位置删除并左移 |
| `traverse(nums, size)` | 遍历并统计 |
| `find(nums, size, target)` | 线性查找，返回下标或 -1 |

## 对照与差异（写完才填）

| 我的实现 | 上游 array.cpp | 差异 | 我的结论 |
|---|---|---|---|
| | | | |

## 验收

- 每个函数都能解释时间复杂度与边界条件；
- 能说出数组与链表在插入/访问上的取舍；
- 以上两条能讲清楚，才算完成，代码能跑不算。
