# [数据结构与算法---python](https://gwt9970161.github.io/Data-structue-and-algorithym-python/)

[学习路线](https://gwt9970161.github.io/Think-Different/)

本笔记旨在从头学习数据结构与算法的重要知识点

数据结构是计算机科学的基础，有助于编写任何语言的高效程序。本笔记基于python这一语言进行学习。

该视频或许可以帮助快速了解：[数据结构与算法预备知识](https://www.bilibili.com/video/BV1Lk4y117Cb?from=search&seid=7505795234012664466&spm_id_from=333.337.0.0)

## 常见数据结构：

### 线性数据结构：
以顺序方式存储数据元素的数据结构。

| Structure | Description |
| --- | ----------- |
| [数组(Array)](https://gwt9970161.github.io/Array/) | 它是与数据元素的索引配对的顺序排列 |
| [链表(Linked List) ](https://gwt9970161.github.io/Linkedist/)| 每个数据元素都包含指向另一个元素的链接以及其中的数据 |
| 数组(Array) | 它是与数据元素的索引配对的顺序排列 |
| 栈(Stack) | 它是一种数据结构，仅遵循特定的操作顺序。LIFO(Last In First Out，后进先出)或者(First In Last Out. 先进后出) |
| 队列(Queue) | 它与Stack类似，但操作顺序仅为FIFO(First In First Out，先进先出) |
| 矩阵(Matrix) | 二维数据结构，其中数据元素由一对索引引用 |

### 非线性数据结构
这些数据结构中没有数据元素的顺序链接。任何一对或数据元素都可以相互链接，并且可以在没有严格序列的情况下访问。

| Structure | Description |
| --- | ----------- |
| 二叉树(Binary Tree) | 这是一种数据结构，其中每个数据元素可以连接到最多两个其他数据元素 |
| 堆(Heap） | 这是树数据结构的一种特殊情况，其中父节点中的数据严格大于/等于子节点或严格小于其子节点 |
| 哈希表(Hash Table) | 这是一种数据结构，由散列函数相互关联的数组组成。它使用键而不是数据元素的索引来检索值 |
| 图(Graph) | 它是顶点和节点的排列，其中一些节点通过链接互相连接 |

### Python特定数据结构
这些数据结构特定与Python语言，他们为在python环境中存储不同类型的数据和更快的处理提供了更大的灵活性

| Structure | Description |
| --- | ----------- |
| 列表(List) | 它类似于数组，但数据元素可以是不同的数据类型。可以在python列表中同时包含数字和字符串数据 |
| 元组(Tuple） | 元组类似于列表，但他们是不可变的，这意味着元组中的值不可修改，只能读取 |
| 字典(Dictionary) | 字典包含键值对作为其数据元素 |

