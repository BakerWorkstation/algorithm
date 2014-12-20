algorithm
=========

在阅读算法导论的时候。我用Python写的一些算法，这些算法大部分使用list来作为底层存储数据的结构。但是python的list用的是链表实现，因此有些操作性能不高。

#算法
-------------
##排序算法：sort文件夹下面
1.  冒泡排序
2.  插入排序
3.  归并排序
4.  快速排序
5.  随机快速排序
6.  选择排序
7.  堆排序
8.  计数排序


##查找算法
1.  二分查找算法
2.  第k小数选择算法
3.  随机第k小数选择算法
4.  计算集合中两个元素的和和一个数相等

##动态规划
1.  使用分治法的最大子数组（应该算成分治法）
2.  使用自底向上方法实现的最大子数组
3.  使用动态规划的两种方式实现的LCS（最大公共串）（下面的算法都会使用动态规划的两种方式来实现）
4.  加权有向无环图中最短路径和最长路径

###幂乘：算法复杂度是O(lgn)

###斐波那契树
1.  使用循环实现的算法o(n)


#数据结构
------------
##树
1.  二叉树
2.  使用左孩子右兄弟实现的多叉树
3.  二叉搜索树
4.  红黑树
5.  动态顺序统计树
6.  区间树
7.  AVL树（未实现，类似于红黑树）
8.  Tries(用于处理字符串)
9.  B树(B树的中序遍历是由我自己实现的，没有任何资料来源)

##列表类
1.  双向链表
2.  使用三个数组实现的链表
3.  跳跃表 （性能类似于红黑树，但是编程更加简单）
4.  栈

##堆类和队列
1.  最大堆
2.  最大优先队列
3.  使用列表实现的队列
4.  使用最大堆实现的FIFO队列

##哈希表
1.  使用链表解决冲突的哈希表
2.  使用二次哈希解决冲突的哈希表

##矩阵
1.  实现strassen矩阵乘法的矩阵

##图
1.  深度遍历，广度遍历和拓扑排序
2.  带权有向无环图的最大路径（动态规划自下而上）


##类库：为了保证被其他算法使用的数据结构一定是没有bug的，我用Python的内置类型实现实现了一些常用的数据结构(lib)
1.  Stack
2.  Queue
3.  Set




