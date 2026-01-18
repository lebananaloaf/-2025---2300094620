## Assignment 1:

袋子里最少数目的球

note：二分查找

String Task

.lower(), .upper()

add to a string: use append

Goldbach Conjecture

\*\* is sqrt

% is remainder

多项式时间复杂度

## Assignment 3

移动零

use a pointer to indicate which position you want to keep track

有效的括号

mapping pairs is cruical for this question

stack operations

- stack\[\]
- stack append()
- stack.pop()

not stack = if it is empty

杨辉三角

## Assignment 4

矩阵运算

w

the importnat thing is t**o compare column and rows, assign correctly.**

draw out the matrix, understand who is mulitplying who

二维矩阵上的卷积运算

倒排索引

use a dictionary to match values to items

use continue to skiip the loop once for this iteration

相交链表

反转链表

## Mock Exam Assignment 5

咒语序列

We iterate through the string using enumerate.

If the character is '(', we push its **index** onto the stack.

If the character is ')', we pop from the stack to try to match it.

- If the stack becomes empty after popping, we push the current index as a new base (this ) is invalid).
- Otherwise, we update the maximum length using

**i - stack\[-1\]**.

八皇后

USE DFS

- check for conlfict cases, like same column, diagonal
- backtracking
    - trying a choice, continuing if it works, undoinging it if it leads to a dead end

洋葱

#NAVIGATE TOP DOWN LEFT RIGHT BY HOLDING ONE OF THEM CONSTANT

find patterns in finding layers

find patterns in finding where each layer is

you just have to write out the indexes and compare it to find a function

检测括号嵌套

字符串中可能有3种成对的括号，"( )"、"\[ \]"、"{}"。请判断字符串的括号是否都正确配对以及有⽆括号嵌套

## Assignment 6：链表，栈, 排序

后续表达式求值

回文链表

有多少种合法的出栈顺序

中序表达式转后续表达式

## Assignment 7: BFS

二叉树的层序遍历

For BFS on a tree, you need:

1.  **A queue** (usually collections.deque)
2.  **An initial element** (the root)
3.  **A loop while the queue is not empty**
4.  **Level control** (know how many nodes are in the current level)
5.  **Add children to the queue**

分割回文串

https://leetcode.cn/problems/palindrome-partitioning/

岛屿数量

https://leetcode.cn/problems/number-of-islands/

DFS is good when:You want to fully explore one connected region， Mark everything visited，Then move on to find the next region

High-level DFS strategy

1.  Traverse every cell in the grid
2.  When you see a '1':
    1.  You’ve found a new island
    2.  Increment island count
    3.  Use DFS to flood-fill the entire island (mark it visited)
3.  Continue scanning the grid

DFS essentials (mental checklist)

1.  Boundary check
    1.  dont go out of bounds
    2.  follow the rules/dont revisit nodes
2.  Base case (water or already visited)
3.  Mark visited
4.  Explore neighbors recursively

how to mark “visited”

Two common methods:

Option A (most common): modify the grid

Option B: separate visited set

最深叶节点的最近公共祖先

https://leetcode.cn/problems/lowest-common-ancestor-of-deepest-leaves/

单词搜索

https://leetcode.cn/problems/word-search/

顺序查索

直接插入排序 二分插入排序

冒泡排序