
Table of Contents
=================

   * [数据结构](#数据结构)
      * [数组和String](#数组和string)
      * [链表](#链表)
            * [基础](#基础)
            * [常见题](#常见题)
      * [树](#树)
         * [二叉树](#二叉树)
            * [基础](#基础-1)
            * [常见题：](#常见题-1)
         * [二叉搜索树](#二叉搜索树)
         * [平衡二叉树](#平衡二叉树)
      * [图](#图)
      * [查找](#查找)
         * [顺序查找](#顺序查找)
         * [二分查找 o(nlog(n))](#二分查找-onlogn)
         * [分块查找](#分块查找)
         * [B树和B 树查找](#b树和b树查找)
         * [hash表查找 o(1)](#hash表查找-o1)
      * [排序](#排序)
         * [插入排序](#插入排序)
            * [直接插入排序](#直接插入排序)
            * [折半插入排序](#折半插入排序)
            * [希尔排序](#希尔排序)
         * [交互排序](#交互排序)
            * [冒泡排序](#冒泡排序)
            * [快速排序](#快速排序)
         * [选择排序](#选择排序)
            * [简单选择排序](#简单选择排序)
            * [堆排序](#堆排序)
         * [归并排序](#归并排序)
         * [基数排序](#基数排序)
   * [算法题常见套路](#算法题常见套路)
      * [最常考算法题](#最常考算法题)
      * [字符串和数组](#字符串和数组)
      * [数字处理](#数字处理)
      * [搜索、递归、回溯](#搜索递归回溯)
         * [做搜索、回溯问题的套路是画图，代码其实就是根据画出的树形图写出来的。](#做搜索回溯问题的套路是画图代码其实就是根据画出的树形图写出来的)
      * [动态规划](#动态规划)
         * [定义：动态规划一般应用于组合优化问题，这种问题一般由一个对应的目标函数和约束条件，能有效 <strong>利用前面已经得到的结果</strong> ，最大限度减少重复工作，以提高算法效率，但是一般往往消耗更多储存](#定义动态规划一般应用于组合优化问题这种问题一般由一个对应的目标函数和约束条件能有效-利用前面已经得到的结果-最大限度减少重复工作以提高算法效率但是一般往往消耗更多储存)
            * [<a href="https://leetcode-cn.com/problems/edit-distance/solution/bian-ji-ju-chi-mian-shi-ti-xiang-jie-by-labuladong/" rel="nofollow">编辑距离</a> <em>重点</em>](#编辑距离-重点)
      * [双指针](#双指针)
            * [<a href="https://leetcode-cn.com/problems/merge-sorted-array/solution/he-bing-liang-ge-you-xu-shu-zu-by-leetcode/" rel="nofollow">合并两个有序数组</a>](#合并两个有序数组)
      * [操作系统和redis相关使用的算法](#操作系统和redis相关使用的算法)
   * [智力题](#智力题)
   * [计算机基础](#计算机基础)
      * [操作系统](#操作系统)
      * [计算机网络](#计算机网络)
   * [java 相关](#java-相关)
      * [集合相关](#集合相关)
      * [IO相关](#io相关)
      * [线程相关](#线程相关)
      * [常见考题](#常见考题)
      * [linux 命令常见面试题](#linux-命令常见面试题)
      * [JVM](#jvm)
   * [redis相关](#redis相关)
      * [知识点](#知识点)
      * [大数据算法相关](#大数据算法相关)
      * [项目实战](#项目实战)
   * [mysql相关](#mysql相关)
   * [spring 相关](#spring-相关)
      * [spring mysql操作](#spring-mysql操作)
      * [spring aop](#spring-aop)
      * [spring ioc](#spring-ioc)
      * [spring 中的设计模式](#spring-中的设计模式)
   * [netty参数](#netty参数)
   * [kafka 相关](#kafka-相关)
   * [公司面试](#公司面试)
      * [<a href="https://mp.weixin.qq.com/s/REBPmDPLqxmzTUXU6Cmg7A" rel="nofollow">头条(校招)：</a>](#头条校招)
         * [字节跳动技术一面](#字节跳动技术一面)
         * [字节跳动技术二面](#字节跳动技术二面)
         * [字节跳动技术三面](#字节跳动技术三面)
         * [字节跳动技术四面](#字节跳动技术四面)
      * [<a href="https://yq.aliyun.com/articles/682816" rel="nofollow">快手(社招)：</a>](#快手社招)
         * [<strong>一面(一个小时十分钟)</strong>](#一面一个小时十分钟)
         * [二面(四十多分钟)](#二面四十多分钟)
         * [三面(50分钟：主要分布式这块)](#三面50分钟主要分布式这块)
   * [项目相关：](#项目相关)
      * [instaclip:](#instaclip)

Created by [gh-md-toc](https://github.com/ekalinin/github-markdown-toc)
# 数据结构

## 数组和String

1. 数组a,先单调地址再单调递减，输出数组中不同元素个数。要求：O(1)空间复杂度，不能改变原数组 看

## 链表

#### 基础

1. 头插法
2. 尾插法
3. 双向链表

#### 常见题

1. [反转单链表](https://leetcode-cn.com/problems/reverse-linked-list/solution/dong-hua-yan-shi-206-fan-zhuan-lian-biao-by-user74/) 
2. [复制复杂列表](https://blog.csdn.net/dawn_after_dark/article/details/80979501) 
3. [最长公共前缀](https://leetcode-cn.com/problems/longest-common-prefix/solution/zui-chang-gong-gong-qian-zhui-by-leetcode/)

## 树

### 二叉树

#### 基础

1. 递归的先序、中序、后序 o(n)
2. 非递归的先序、中序、后序（复杂）o(n)
3. 层次遍历  o(n)

#### 常见题：

1. 检查是否为平衡二叉树（高度差不超过1），o(n)
2. 给定有序数组创建二叉查找树 o(log(n))
3. 计算数每层的节点 o(n)
4. 判断某树是二叉查找树 最小最大法
5. [判断镜像二叉树](https://blog.csdn.net/hansionz/article/details/81911353)
6. 求树的高度 递归 非递归 《数据结构 p122 4》
7. 用先序序列和中序序列构建树 《数据结构 p131 4》


### 二叉搜索树

### 平衡二叉树

###B树、B+树

1. 应用：数据库、文件系统、epoll

## 图

1. DFS BFS
2. 查找两节点是否存在一条路径

## 查找

### 顺序查找

### 二分查找 o(nlog(n))

### 分块查找

### B树和B+树查找

### hash表查找 o(1)

## 排序

### 插入排序

####  直接插入排序 

####  折半插入排序 

####  希尔排序 

### 交互排序

####  冒泡排序 

####  快速排序 

### 选择排序

####  简单选择排序 

####  堆排序 

1. 构建大根堆

### 归并排序

### 基数排序















# 算法题常见套路

## 最常考算法题

1. 写一个单例，要求用double check, volatile, 解释volatile的意义，为什么要用double check
2. 写一个树的层次遍历，求深度
3. 写一个树的后序遍历，中序遍历，先序遍历 ， 要求非递归式
4. 写一个快排，问快排是否是稳定的，怎么优化快排
5. 写一个堆排序
6. 写一个n个有序数组的归并排序，要求时间复杂度和空间复杂度最好


##  字符串和数组

 1.判断是否有重复字段，或者是变位词问题  （hashmap、位运算、set   面经p121)
 2.[电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number/)  （字母组合问题 递归和回溯 ）
 3.[无重复字符的最长子串](https://leetcode-cn.com/problems/longest-substring-without-repeating-characters/) （用 HashSet，HashMap 作为滑动窗口，ij作为滑动变量   滑动窗口问题  )
 4.[最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring/) （动态规划问题 dp)

## 数字处理

 1.十进制求余、求商 （%10 、/10  [快乐数]([https://leetcode-cn.com/problems/happy-number/submissions/]))
 2.

## 搜索、递归、回溯

### 做搜索、回溯问题的套路是画图，代码其实就是根据画出的树形图写出来的。

1. [电话号码的字母组合](https://leetcode-cn.com/problems/letter-combinations-of-a-phone-number/)  （字母组合问题 递归和回溯 ）





## 动态规划

### 定义：动态规划一般应用于组合优化问题，这种问题一般由一个对应的目标函数和约束条件，能有效 **利用前面已经得到的结果** ，最大限度减少重复工作，以提高算法效率，但是一般往往消耗更多储存

1. 背包问题

2. 图的多起点和多终点的最短路劲问题

3. [最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring/solution/xiang-xi-tong-su-de-si-lu-fen-xi-duo-jie-fa-bao-gu/)

4. [组合总和](https://leetcode-cn.com/problems/combination-sum/solution/chao-qiang-gifzhu-ni-shi-yong-dong-tai-gui-hua-qiu/)

5. #### [编辑距离](https://leetcode-cn.com/problems/edit-distance/solution/bian-ji-ju-chi-mian-shi-ti-xiang-jie-by-labuladong/) *重点*

## 双指针

1. [Leetcode](https://blog.csdn.net/pushup8/article/details/85071735) 

2. [有序数组两数之和](https://leetcode-cn.com/problems/two-sum-ii-input-array-is-sorted/solution/shuang-zhi-zhen-on-shi-jian-fu-za-du-by-cyc2018/) [无序数组两数之和](https://leetcode-cn.com/problems/two-sum/solution/liang-shu-zhi-he-by-leetcode-2/) [3Sum](https://leetcode-cn.com/problems/3sum/solution/hua-jie-suan-fa-15-san-shu-zhi-he-by-guanpengchn/) （前后指针）

3. [移除元素](https://leetcode-cn.com/problems/remove-element/solution/yi-chu-yuan-su-by-leetcode/) [移动零](https://leetcode-cn.com/problems/move-zeroes/solution/javashuang-zhi-zhen-zuo-fa-by-arthur-24/) （快慢指针）

4. #### [合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/solution/he-bing-liang-ge-you-xu-shu-zu-by-leetcode/)

## 操作系统和redis相关使用的算法

1. [LRU](https://blog.csdn.net/qq_26440803/article/details/83795122)
2. [LRU和redis里面的实现](https://zhuanlan.zhihu.com/p/34133067)


# 智力题



# 计算机基础

## 操作系统

1. [进程和线程的区别](https://blog.csdn.net/kuangsonghan/article/details/80674777)

2. [页缓存](https://blog.csdn.net/Joy0709/article/details/41879001) [DMA](https://blog.csdn.net/zhejfl/article/details/82555634) [虚拟内存](https://www.jianshu.com/p/13e337312651)

3. [零拷贝](https://mp.weixin.qq.com/s/WqXU7zfRPeMznOESRphbxg)

4. [Linux 网络 I/O 模型简介](https://my.oschina.net/lvzunwei/blog/687861) 五种 阻塞I/O模型、非阻塞I/O模型、I/O复用模型（多路复用）、信号驱动I/O模型、异步I/O

   其实对应java就三种  阻塞I/O模型、I/O复用模型（多路复用）、异步I/O

5. [select poll epoll](https://zhuanlan.zhihu.com/p/39970630)  

   select 三个缺点：

   文件描述符数量越多，性能越差；

   内核/用户空间内存拷贝问题，需要复制大量的句柄数据结构，产生巨大的开销；

   触发方式是水平触发，应用程序如果没有完成对一个已经就绪的文件描述符进行IO，那么之后再次select调用还是会将这些文件描述符通知进程；

## 计算机网络

1. [TCP 的三次握手和四次捂手](https://blog.csdn.net/bit_clearoff/article/details/60884905) [流程](https://blog.csdn.net/whuslei/article/details/6667471)
2. TCP的滑动窗口原理

# java 相关
## Java 坑
[1.对象比较方法 Objects.equals 
2.三元表达式拆包
3.泛型对象赋值
4.泛型属性拷贝
5.Set对象排重
6.公有方法代理 aop
7.公有字段代理](https://mp.weixin.qq.com/s/edf9qy2Rthl9bzdxSxtAeQ)
8.各种包装和基本类型转化






## 集合相关

1. [HashMap java8 数据结构实现、查找、添加、扩容](https://zhuanlan.zhihu.com/p/21673805) 
2. HashMap几个关键字段threshold，loadFactor，length，size，modCount 其中threshold =length * loadFactor，size超过threshold时就会resize；[多线程下HashMap死循环问题](https://blog.csdn.net/xuefeng0707/article/details/40797085)
3. HashMap的Hash算法：**取key的hashCode值、高位运算、取模运算**
4. [ConcurrentHashMap1.8](https://www.jianshu.com/p/c0642afe03e0) [ConcurrentHashMap1.7和1.8的不同实现](https://www.jianshu.com/p/e694f1e868ec)
5. [ArrayBlockingQueue实现](https://blog.csdn.net/summerZBH123/article/details/80929902)

## IO相关

1. 基础IO、文件操作；NIO中Buffer 和 Channel（其中操作可以结合p2p项目源码看；[IO和NIO的区别](https://baijiahao.baidu.com/s?id=1632673729522644150&wfr=spider&for=pc)；ByteBuffer中的 [BIG_ENDIAN LITTLE_ENDIAN](https://www.cnblogs.com/sys-engineer/archive/2012/10/17/2728033.html) 其中[网络](https://blog.csdn.net/xiuzhentianting/article/details/73836699)和JVM虚拟接中采用BIG-ENDIAN 
2. [BIO、AIO、NIO](https://blog.csdn.net/baiye_xing/article/details/73123753)  [Java 实现代码](https://blog.csdn.net/alan_liuyue/article/details/88640339)
3. [Jdk epoll bug](https://www.jianshu.com/p/3ec120ca46b2) [netty 解决epoll bug](https://blog.csdn.net/baiye_xing/article/details/73351330)

## 线程相关

1. [线程池原理](https://www.jianshu.com/p/87bff5cc8d8c) [线程池状态](https://blog.csdn.net/kuangsonghan/article/details/80674777)  [线程池相关面试题](https://www.nowcoder.com/discuss/152050)
2. [Netty 线程模型](https://www.infoq.cn/article/netty-threading-model) [Netty 高效并发编程](https://blog.csdn.net/baiye_xing/article/details/73351330)
3. 线程三种创建方式、[线程的5个状态和转化](https://blog.csdn.net/xingjing1226/article/details/81977129)、 sleep和yield不同、什么时候放弃同步监视器
4. [synchronized和lock的区别](https://www.cnblogs.com/billmiao/p/9872163.html) [synchronized 原理](https://www.jianshu.com/p/19f861ab749e) [ReentrantLock原理](https://www.jianshu.com/p/4358b1466ec9)（再看）
5. [volatile关键字](https://www.cnblogs.com/dolphin0520/p/3920373.html)：需要保证操作是原子性操作，才能保证使用volatile关键字的程序在并发时能够正确执行，也就是说基本数据类型的数值或者false赋值、volatile和Atomic* 一起使用
6. [CAS](https://www.jianshu.com/p/fb6e91b013cc) [cas的ABA问题的解决方法](https://www.jianshu.com/p/8b227a8adbc1) 和 [使用方法](https://blog.csdn.net/xybz1993/article/details/79992120)
7. [valatile cas -> atomic 无锁操作](https://www.cnblogs.com/dengzz/p/5688021.html)
8. [AQS 原理](https://www.jianshu.com/p/d8eeb31bee5c) [公平锁 非公平锁 图解](https://blog.csdn.net/yanyan19880509/article/details/52435135)  [lock tryLock lockInterruptibly](https://www.zhihu.com/question/36771163)
9. [重入锁](https://blog.csdn.net/u010173095/article/details/78621170)、[独占锁与共享锁](https://www.cnblogs.com/liuling/p/2013-8-21-03.html)（写锁、读锁）、公平锁与非公平锁 （默认false非公平锁，true为公平锁）、[悲观锁与乐观锁](http://blog.itpub.net/69903322/viewspace-2286168/) （synchronized lock 与 cas）
10. [LongAdder](https://blog.csdn.net/zqz_zqz/article/details/70665941)
11. [同步调用，异步回调和 Future 模式](https://blog.csdn.net/qq_35688140/article/details/83115723)
12. [CountDownLatch、CyclicBarrier和Semaphore](https://www.cnblogs.com/dolphin0520/p/3920397.html)
13. [grpc中的同步和异步](https://blog.csdn.net/huweijian5/article/details/83822470#grpc_2)
14. [java有哪些锁？](https://www.cnblogs.com/chinaifae/articles/10338547.html)
15. [AtomicReference](https://blog.csdn.net/chuanwen0451/article/details/100816412)

## 常见考题

1. [单例模式的五种实现方式](https://www.cnblogs.com/zhaoyan001/p/6365064.html)：饿汉式（线程安全）、懒汉式（线程不安全）、懒汉式( 线程安全，synchronized 同步方法，效率太低)、懒汉式( 线程不安全，synchronized 同步代码块，不可用)、双重检查（ 线程不安全，synchronized 同步代码块，二次检查null)、静态内部类、枚举。

   其中饿汉模式、懒汉模式（synchronized方法）、双重检查、静态内部类、枚举这五种可以用。

   2.[DCL](https://blog.csdn.net/qiyei2009/article/details/71813069)



## linux 命令常见面试题

1. [基础命令](https://blog.csdn.net/weixin_38429587/article/details/79110588)

   




## JVM

1. [gc](https://zhuanlan.zhihu.com/p/25539690)算法： **根搜索算法**、**标记 - 清除算法**、**复制算法**、**标记 - 整理算法**

2. [**垃圾回收器**](https://zhuanlan.zhihu.com/p/25539690)：新生代：**Serial**、**ParNew**、**ParallelScavenge**（优先吞吐量）老生代:**SerialOld**、**ParallelOld**、**CMS （-XX:+UseConcMarkSweepGC 优**响应时间**）**

   其中新生代使用复制算法、老生代使用标记-整理算法，除了CMS（ 标记-清理）

   只有Serial、ParNew 和CMS可以一起使用。

3. [jvm的内存分布](https://www.cnblogs.com/wtzbk/p/7985156.html?clicktime=1573004363&enterid=1573004363)（看书）

4. [什么时候进行gc](https://www.zhihu.com/question/41922036/answer/154212925)

5. [G1算法](https://www.cnblogs.com/ityouknow/p/5614961.html)

6. [JVM内存结构、Java内存模型 、Java对象模型](https://mp.weixin.qq.com/s/i_i3aT48NCPukE_6w9Srng)

7. [什么时候进行Minor GC 和 FULL GC](https://blog.csdn.net/varyall/article/details/82527070)

   ​    


# redis相关

## 知识点

1. redis基本命令  (菜鸟命令 结合im项目看 redis相关知识看)
2. redis 底层数据结构[1](https://www.cnblogs.com/jaycekon/p/6227442.html) [2](https://www.cnblogs.com/jaycekon/p/6277653.html) (原理) *要再看 *在看完数据结构的情况下接着看
3. redis 相关题目 ([基础](https://www.cnblogs.com/jasontec/p/9699242.html))
4. redis rdb 和aof [aof](https://redisbook.readthedocs.io/en/latest/internal/aof.html) [rdb](https://redisbook.readthedocs.io/en/latest/internal/rdb.html) [遇到的问题](https://www.iteye.com/blog/xiaoz5919-2093393)、[SAVE BGSAVE BGREWRITEAOF](https://redisbook.readthedocs.io/en/latest/internal/rdb.html)、[AOF RDB持久化高度概括](https://blog.csdn.net/qq_21688757/article/details/79233490)    ***要再看***
5. [缓存穿透，缓存击穿，缓存雪崩](https://blog.csdn.net/zeb_perfect/article/details/54135506)
6. [redis的架构模式](https://www.cnblogs.com/jasontec/p/9699242.html) 单机 主从 [sentinel](https://www.jianshu.com/p/06ab9daf921d)  [proxy](https://juejin.im/post/5c132b076fb9a04a08218eef) cluster
7. [Redis集群方案](https://juejin.im/post/5c132b076fb9a04a08218eef)  Redis cluster [哈希槽](https://blog.csdn.net/z15732621582/article/details/79121213) [一致性hash](https://www.cnblogs.com/lpfuture/p/5796398.html)
8. redis [分布式锁redis 命令](https://blog.csdn.net/lihao21/article/details/49104695)  [分布式锁 java 实现](https://my.oschina.net/dengfuwei/blog/1600681)  (结合cms改版看)
9. [深入浅出Redis-redis底层数据结构（上）](https://www.cnblogs.com/jaycekon/p/6227442.html) [深入浅出Redis-redis底层数据结构（下）](https://www.cnblogs.com/jaycekon/p/6277653.html)
10. [底层数据结构](https://blog.csdn.net/qq_36642340/article/details/81020477)

## 大数据算法相关

1. [两个大文件中找出共同记录](https://blog.csdn.net/u011389515/article/details/80526971)

 

## 项目实战

1. [redis cluster 线上运维](https://blog.csdn.net/AlbertFly/article/details/80360471) [sentinel集群切换](https://static.app.yinxiang.com/embedded-web/profile/#/join?guid=2668aee3-9af5-42fb-b5b3-990d23179e25&channel=copylink&shardId=s57&ownerId=11397930)
2. [Redis bitmap 使用](https://www.jianshu.com/p/ea087619adc8) [亿万级别使用](https://blog.csdn.net/u011957758/article/details/74783347)


# mysql相关

1. [MySQL的四种事务隔离级别](https://www.cnblogs.com/huanongying/p/7021555.html)
2. [MySQL(Innodb)索引的原理](https://www.cnblogs.com/rjzheng/p/9915754.html)
3. [记录锁，间隙锁，next-key锁](https://blog.csdn.net/bigtree_3721/article/details/73731377) [图](https://www.jianshu.com/p/bf862c37c4c9)
4. [mysql/innoDB中，乐观锁，悲观锁，共享锁，排他锁，行锁，表锁，死锁概念的理解](mysql/innoDB中，乐观锁，悲观锁，共享锁，排他锁，行锁，表锁，死锁概念的理解)
5. [Left on/right on](https://blog.csdn.net/qq_35101027/article/details/78288279) [left join和inner join的效率对比](https://blog.csdn.net/LJFPHP/article/details/88635755)
6. [索引优化](https://www.jianshu.com/p/3ffb938a2622)
7. [Mysql中myisam和innodb的区别](http://blog.itpub.net/21374452/viewspace-2136284/)
8. [**普通索引**，**回表**，**索引覆盖**](https://www.jianshu.com/p/8991cbca3854)

 




# spring 相关

## spring mysql操作

1. [@Transactional ](https://blog.csdn.net/nextyu/article/details/78669997)

2. [InnoDB](https://zhuanlan.zhihu.com/p/35811482)

## spring aop

1. [aop原理](https://juejin.im/post/591d8c8ba22b9d00585007dd) [jdk proxy 和 cglib动态代理](https://www.cnblogs.com/CarpenterLee/p/8241042.html) [guava 代理使用](http://outofmemory.cn/java/guava/reflect/Reflection-simplify-Dynamic-proxy)

## spring ioc 

1. [Ioc原理](https://zhuanlan.zhihu.com/p/41274946) [通俗](http://www.voidcn.com/article/p-ryggjrau-bch.html)
2. 几种方式（看书）
3. [ioc解决循环依赖方法](https://zhuanlan.zhihu.com/p/62382615) [源码级别](https://segmentfault.com/a/1190000015221968)

## spring 中的设计模式

1. [7种设计模式](https://juejin.im/post/5ce69379e51d455d877e0ca0#heading-1)
2. [Bean的创建过程](https://www.jianshu.com/p/1dec08d290c1)
3. [proxy和装饰器的区别](https://www.jianshu.com/p/c06a686dae39)

# netty参数

1. [ChannelOption参数详解](https://www.jianshu.com/p/975b30171352)
2. ChannelOption.SO_BACKLOG  ChannelOption.TCP_NODELAY ALLOW_HALF_CLOSURE
3. [nettty调参](https://www.cnblogs.com/cfas/p/10422108.html)
4. [编解码](https://blog.csdn.net/weixin_37855731/article/details/83506941)
5. https://www.jianshu.com/p/a618adef427c

# kafka 相关

1. kafka 如何做到高吞吐量、低延时；负载均衡和故障转移；伸缩性（zk保持。
2. kakfa topic-partition-message
3. 怎么做数据恢复的？数据会不会漏？
4. [kafka consumer两种消费方式](https://www.jianshu.com/p/0a05633978f0)
5. [TimingWheel 时间轮详解](https://blog.csdn.net/u013332124/article/details/82119144)
6. [kafka语义](https://blog.csdn.net/laojiaqi/article/details/79034798)

# 公司面试

## [头条(校招)：](https://mp.weixin.qq.com/s/REBPmDPLqxmzTUXU6Cmg7A)

### 字节跳动技术一面

一面问的都还比较基础，答得也还算顺利

- 说下你的实习项目吧
- 讲一下线程参数的含义
- Innodb的索引实现
- 为什么是B+树？
- Redis的使用，分布式锁的实现
- 操作系统虚拟内存换页的过程
- TCP三次握手
- volatile关键字的作用
- 乐观锁、悲观锁
- HashMap结构，是否线程安全？ConcurrentHashMap如何保证线程安全？
- 之前用过哪些设计模式？
- 算法题：滑动窗口

### 字节跳动技术二面

发现字节的面试官都挺年轻的，头发也没怎么秃，哈哈~

- 说一下B树和B+树的区别
- 说一下HashMap的实现，扩容机制，扩容时如何保证可操作？
- Redis扩容机制（渐进式单线程扩容）
- Spring AOP的原理
- Spring IoC的原理，如何实现，如何解决循环依赖？
- 两线程对变量i进行加1操作，结果如何？为什么？怎么解决？
- CAS概念、原子类实现原理
- synchronize底层实现，如何实现Lock？
- AQS有什么特点？
- 手写项目中某个模块代码。
- 介绍各种网络协议。
- DNS在网络层用哪个协议，为什么。
- 介绍HTTPS协议，详述SSL建立连接过程。
- 代码题：反转单链表。
- 代码题：复杂链表复制。
- 代码题：数组a,先单调地址再单调递减，输出数组中不同元素个数。要求：O(1)空间复杂度，不能改变原数组

### 字节跳动技术三面

算法题多到爆炸，感觉是算法专场，宇宙条果真名不虚传

- 说一下Java垃圾回收机制
- 64匹马，8个赛道，找最快的4匹马。
- 64匹马，8个赛道，找最快的8匹马。
- 给出两个升序数组A、B和长度m、n，求第k个大的数
- 给出数组A，长度为n，数组中元素的值位于[0, n - 1]之间，求是否有重复元素
- 讲一下多线程与多进程区别
- JVM中什么时候会进行垃圾回收？什么样的对象是可以回收的？
- Spring主要思想是什么？
- 你未来的发展方向是什么？确定了么？打算一直做Java？有考虑过转吗？
- 那你平时是怎么学习Java的呢？
- 分享最近看的一本书

### 字节跳动技术四面

那天状态不佳，面试官也没有问太多问题，以为没戏了

- 场景题目：设计一个短域名服务：短信存不了太长网站，需要弄成短域名，你该如何设计一个服务，可以为全国的网址服务。
- TCP为什么是三次握手四次挥手？
- 数据库的隔离级别
- sql题，写了个连表查询外加模糊查询
- 算法：镜像二叉树 ......

## [快手(社招)：](https://yq.aliyun.com/articles/682816)

### **一面(一个小时十分钟)**

1.自我介绍

2.说说B+树和B树的区别，优缺点等？

3聊聊Spring，主要IOC等等

4多线程JUC包下的一些常见的类，比如CountDownLatch、Semaphore等

5.锁的概念，锁相关的关键字，volatile，synchronized。还比较了ReentrantLock与synchronized。

6.你了解哪些收集器？CMS和G1。详细谈谈G1的优点？什么时候进行Full GC呢？

7.Spring中涉及的一些设计模式

8.算法题：无序数列中求第k大的数(维护最小堆，然后依次遍历，与堆顶比较)

9.MySQL创建索引的原则，好处

10.怎么实现一个线程安全的计数器？

### 二面(四十多分钟)

1. 设计模式：讲了单例，工厂方法，抽象工厂，策略模式，观察者模式，代理模式，还顺便讲了下spring动态代理的实现原理
2. 线程池有哪些参数？分别有什么用？如果任务数超过的核心线程数，会发生什么？阻塞队列大小是多少？
3. HashMap的底层数据结构
4. 红黑树的具体结构及实现，红黑树与查找树的区别体现
5. 接着聊ConcurrentHashMap，底层实现
6. HashMap哈希函数的认识，JDK1.8采用的hash函数
7. 数据库索引，索引底层的实现，B+树的结构以及与普通查找树的优点
8. TCP三次握手四次挥手，四次挥手过程中服务端的哪几种状态，哪几种包
9. 已经有一个查询好友的接口，设计一个微信朋友圈，可以实现发表朋友圈，添加评论，查看评论等功能。主要是设计数据结构

### 三面(50分钟：主要分布式这块)

你对快手的了解，和抖音的区别，聊项目
项目中用到dubbo？那你说说什么是rpc框架？和http调用的区别是什么？
Redis有哪些数据结构？持久化方案和区别？
Redis哨兵、集群的设计原理和区别？
Redis缓存和数据库会存在一致性问题吗？怎么解决
Kafka怎么保证数据可靠性？讲了生产者端发送消息到broker持久化，分区和副本机制，消费者消费消息的at-least-once和at-most-once？怎么实现Exactly-Once？

## 百度
面试时候，让手写一个多生产者多消费者，一个无锁队列

# 项目相关：




