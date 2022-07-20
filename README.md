
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

### [二叉树](https://leetcode-cn.com/problems/binary-tree-preorder-traversal/solution/tu-jie-er-cha-shu-de-si-chong-bian-li-by-z1m/)

#### [基础](https://leetcode-cn.com/problems/binary-tree-preorder-traversal/solution/leetcodesuan-fa-xiu-lian-dong-hua-yan-shi-xbian-2/)

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

####   DFS BFS

####   查找两节点是否存在一条路径

####   二分图



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

## 搜索、递归、回溯（就是树的遍历）

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

3. #### [合并两个有序数组](https://leetcode-cn.com/problems/merge-sorted-array/solution/he-bing-liang-ge-you-xu-shu-zu-by-leetcode/)

4. [盛最多水容器](https://leetcode-cn.com/problems/container-with-most-water/)

 ## 快慢指针

1.[寻找重复数](https://leetcode-cn.com/problems/find-the-duplicate-number/)

2.[环形链表](https://leetcode-cn.com/problems/linked-list-cycle/)

3.[移除元素](https://leetcode-cn.com/problems/remove-element/solution/yi-chu-yuan-su-by-leetcode/) [移动零](https://leetcode-cn.com/problems/move-zeroes/solution/javashuang-zhi-zhen-zuo-fa-by-arthur-24/) （快慢指针）

## 奇葩算法

#### 并查集

1.[头条坐一起](https://blog.csdn.net/weixin_34033624/article/details/88751113) 

#### [匈牙利算法](https://zhuanlan.zhihu.com/p/96229700)


## 操作系统和redis相关使用的算法

1. [LRU](https://blog.csdn.net/qq_26440803/article/details/83795122)

2. [LRU和redis里面的实现](https://zhuanlan.zhihu.com/p/34133067)

3. 布隆过滤器使用场景

   1. 黑名单校验

   2. 快速去重

   3. 爬虫URL校验

   4. leveldb/rocksdb快速判断数据是否已经block中，避免频繁访问磁盘

   5. 解决缓存穿透问题

      计数布隆过滤器

## 面试公司算法

1.  [岛屿的最大面积](https://leetcode-cn.com/problems/max-area-of-island/description/)

2. [分数排名](https://leetcode-cn.com/problems/rank-scores/description/)




# 智力题

## [java](https://honeypps.com/java/7-most-popular-java-questions-on-stackoverflow/)

# 计算机基础

## 操作系统

1. [进程和线程的区别](https://blog.csdn.net/kuangsonghan/article/details/80674777)

1. [进程、线程及协程的区别](https://blog.csdn.net/weixin_49199646/article/details/109210547)

2. [页缓存](https://blog.csdn.net/Joy0709/article/details/41879001) [DMA](https://blog.csdn.net/zhejfl/article/details/82555634) [虚拟内存](https://www.jianshu.com/p/13e337312651)

3. [零拷贝](https://mp.weixin.qq.com/s/WqXU7zfRPeMznOESRphbxg)

4. [Linux 网络 I/O 模型简介](https://my.oschina.net/lvzunwei/blog/687861) 五种 阻塞I/O模型、非阻塞I/O模型、I/O复用模型（多路复用）、信号驱动I/O模型、异步I/O

   其实对应java就三种  阻塞I/O模型、I/O复用模型（多路复用）、异步I/O

5. [select poll epoll](https://zhuanlan.zhihu.com/p/39970630)  

   select 三个缺点：

   文件描述符数量越多，性能越差；

   内核/用户空间内存拷贝问题，需要复制大量的句柄数据结构，产生巨大的开销；

   触发方式是水平触发，应用程序如果没有完成对一个已经就绪的文件描述符进行IO，那么之后再次select调用还是会将这些文件描述符通知进程；
   
6. [文件描述符/文件句柄/文件指针的区别与联系](https://www.jianshu.com/p/ad879061edb2)

​     **文件描述符是进程级别的，文件句柄是系统级别的**，不能混用。它们在不同级别表示已打开的文件。

​      文件描述符与文件句柄直接关联，文件句柄与inode直接关联。

​      文件描述符在POSIX系统调用中直接可见，文件指针是C语言在其基础上的包装。

​      文件句柄在UNIX里不是个正式概念，所以无论在系统还是C语言API中都不显式存在。





## 计算机网络

1. [TCP 的三次握手和四次捂手](https://blog.csdn.net/bit_clearoff/article/details/60884905) [流程](https://blog.csdn.net/whuslei/article/details/6667471)
2. TCP的滑动窗口原理
2. `[syns queue`（半连接队列）和`accept queue`（全连接队列）](https://www.cnblogs.com/wx170119/p/12068005.html)
2. [tcp 发送缓冲区 和 接收缓冲区](https://www.teqng.com/2021/07/21/%e5%8a%a8%e5%9b%be%e5%9b%be%e8%a7%a3%ef%bc%81%e4%bb%a3%e7%a0%81%e6%89%a7%e8%a1%8csend%e6%88%90%e5%8a%9f%e5%90%8e%ef%bc%8c%e6%95%b0%e6%8d%ae%e5%b0%b1%e5%8f%91%e5%87%ba%e5%8e%bb%e4%ba%86%e5%90%97/#shen_me_shi_socket_huan_chong_qu) 
2. [RTT](https://blog.csdn.net/qq_38890412/article/details/106663674) [MSL](https://blog.51cto.com/wushank/1135060)
2. epoll 边缘触发 和水平触发区别 ss
2. [tcp为什么用三次握手](https://blog.csdn.net/lengxiao1993/article/details/82771768) [书里的解释](http://www.justdojava.com/2021/03/28/tcp/)
2. [tcp为什么必须四次挥手](http://www.justdojava.com/2021/03/28/tcp/) [是否有三次挥手](https://www.cnblogs.com/GuoXinxin/p/11657933.html)
2. [长连接、短连接、长轮询、短轮询、WebSocket释疑](https://segmentfault.com/a/1190000020427990)
2. [四层负载均衡 和 七层负载均衡](https://www.modb.pro/db/190731)
2. [lvs架构](https://blog.csdn.net/w50feng/article/details/118028881) [lvs架构和原理和四种模式](https://www.modb.pro/db/190731)
2. [负载均衡](https://www.modb.pro/db/79441)
2. [网卡bond](https://www.linuxprobe.com/actual-combat-nic-bond.html)
2. [NAT FULLNAT 模式](https://blog.csdn.net/m0_37740029/article/details/117248710)
2. [dpvs简介和原理和优化](https://zhuanlan.zhihu.com/p/344194786)
2. [dpvs支持高可用](https://blog.51cto.com/u_15282126/2947767)

      目前线上有上千条业务转发规则，每天承接着来自公司内部、外部共近 5T的服务带宽和 1Billion并发连接量。下图是我们一种常用的 DPVS集群化部署方式：多台 DPVS服务器通过c构成一个服务集群，每台 DPVS服务器配置多台 nginx作为其后端服务器，nginx   以反向代理的方式为最终的应用服务器提供七层负载均衡和高可用性服务。这是一种高可用、高伸缩性的集群化方式，任何一台 APPServer或中间转发节点的故障不会影响整体服务，四层负载均衡器 DPVS、七层反向代理服务器 nginx和应用服务器都能在不影响现有服务的条件下很方便地完成扩容。
![img](https://oss-emcsprod-public.modb.pro/wechatSpider/modb_20211207_8a44f798-5701-11ec-8cf6-fa163eb4f6be.png)

17. [dpvs集群模式](https://cloud.tencent.com/developer/news/841720)
18. [BGP 会话的负载平衡](https://www.juniper.net/documentation/cn/zh/software/junos/bgp/topics/topic-map/load-balancing-bgp-session.html)

# java 相关 

[Java 全栈知识体系](https://www.pdai.tech/)

## Java 坑
[1.对象比较方法 Objects.equals 
2.三元表达式拆包
3.泛型对象赋值
4.泛型属性拷贝
5.Set对象排重
6.公有方法代理 aop
7.公有字段代理](https://mp.weixin.qq.com/s/edf9qy2Rthl9bzdxSxtAeQ)
8.各种包装和基本类型转化

9.sb的java [char类型转化](https://leetcode-cn.com/problems/replace-all-s-to-avoid-consecutive-repeating-characters/)

https://blog.csdn.net/qq_36323559/article/details/98183445

https://www.delftstack.com/zh/howto/java/empty-character-literal-java/



## 基本类型相关
1. [ String#intern](https://tech.meituan.com/2014/03/06/in-depth-understanding-string-intern.html)
  
2. [从JVM角度比较equals和==的区别](https://blog.csdn.net/seu_calvin/article/details/52089040)
3. [String、StringBuider以及StringBuffer的区别和使用场景](https://blog.csdn.net/seu_calvin/article/details/52094905)




## 基本集合相关

1. [ArrayList与LinkedList的区别](https://www.cnblogs.com/zhukf/p/13713533.html)  [LinkedList原理](https://www.cnblogs.com/baojun/p/11087015.html)  [ArrayList扩容机制](https://zhuanlan.zhihu.com/p/409503569)

1. [HashMap java8 数据结构实现、查找、添加、扩容](https://zhuanlan.zhihu.com/p/21673805) 为什么扩容后的HashMap容量是之前容量的两倍？快

   只需要看看原来的hash值新增的那个bit是1还是0就好了，是0的话索引没变，是1的话索引变成“原索引+oldCap”

2. HashMap几个关键字段threshold，loadFactor，length，size，modCount 其中threshold =length * loadFactor，size超过threshold时就会resize；[多线程下HashMap死循环问题](https://blog.csdn.net/xuefeng0707/article/details/40797085)

3. HashMap的Hash算法：**取key的hashCode值、高位运算、取模运算**

4. [ConcurrentHashMap1.8](https://www.jianshu.com/p/c0642afe03e0) [ConcurrentHashMap1.7和1.8的不同实现](https://www.jianshu.com/p/e694f1e868ec)

5. [ArrayBlockingQueue实现](https://blog.csdn.net/summerZBH123/article/details/80929902)

5. [HashMap LinkedHahsMap TreeMap](https://juejin.cn/post/6844904069648089102)

5. ArrayList LinkedList 区别

5. [Set和Map的关系](https://blog.csdn.net/yangying496875002/article/details/73729290)

6. Random

   ![image-20220308184023598](/Users/momo/Library/Application Support/typora-user-images/image-20220308184023598.png)

## 高级集合

   

## 高级java类型

1. CopyOnWriteArrayList [CopyOnWriteArraySet](https://www.jianshu.com/p/f55bf8a8520e)
2. [BlockingQueue ConcurrentLinkedQueue](https://www.cnblogs.com/linjiqin/archive/2013/05/30/3108188.html)  [Blocking](https://www.jianshu.com/p/b1408e3e3bb4)

## Date相关

1. [`SimpleDateFormat` 线程不安全的解决方案](https://segmentfault.com/a/1190000040010020)

## IO相关

1. 基础IO、文件操作；NIO中Buffer 和 Channel（其中操作可以结合p2p项目源码看；[IO和NIO的区别](https://baijiahao.baidu.com/s?id=1632673729522644150&wfr=spider&for=pc)；ByteBuffer中的 [BIG_ENDIAN LITTLE_ENDIAN](https://www.cnblogs.com/sys-engineer/archive/2012/10/17/2728033.html) 其中[网络](https://blog.csdn.net/xiuzhentianting/article/details/73836699)和JVM虚拟接中采用BIG-ENDIAN 
2. [BIO、AIO、NIO](https://blog.csdn.net/baiye_xing/article/details/73123753)  [Java 实现代码](https://blog.csdn.net/alan_liuyue/article/details/88640339)
3. [Jdk epoll bug](https://www.jianshu.com/p/3ec120ca46b2) [netty 解决epoll bug](https://blog.csdn.net/baiye_xing/article/details/73351330)
4. [ByteBuffer直接用堆外内存](https://blog.csdn.net/u014590757/article/details/79856425) [ByteBuffer大端](https://www.cnblogs.com/naughtycat/p/little-endian-and-big-endian-based-on-bytebuffer-in-java.html)
4. [epoll 边缘触发 和水平触发区别](https://juejin.cn/post/6844903878685622285)

## 线程相关

1. [线程池原理](https://www.jianshu.com/p/87bff5cc8d8c) [线程池状态](https://blog.csdn.net/kuangsonghan/article/details/80674777)  [线程池相关面试题](https://www.nowcoder.com/discuss/152050) 线程数核心个数和最大个数设置大小

2. [Netty 线程模型](https://www.infoq.cn/article/netty-threading-model) [Netty 高效并发编程](https://blog.csdn.net/baiye_xing/article/details/73351330)

3. [线程三种创建方式、 sleep和yield不同、什么时候放弃同步监视器、Java线程的六种状态以及切换](https://segmentfault.com/a/1190000038392244)

3. [Thread.interrupt()到底做了啥 ](https://www.jianshu.com/p/e2b22c6bcd22)[LockSupport](https://blog.csdn.net/aitangyong/article/details/38373137)

4. [synchronized和lock的区别](https://www.cnblogs.com/billmiao/p/9872163.html) [synchronized 原理](https://www.jianshu.com/p/19f861ab749e) [ReentrantLock原理](https://www.jianshu.com/p/4358b1466ec9)（再看）

4. [AQS详解](https://tech.meituan.com/2019/12/05/aqs-theory-and-apply.html)

4. sychronized也支持可重入锁

4. [偏向锁，轻量级锁， 重量级锁](https://blog.csdn.net/lengxiao1993/article/details/81568130)

5. [volatile关键字](https://www.cnblogs.com/dolphin0520/p/3920373.html)：需要保证操作是原子性操作，才能保证使用volatile关键字的程序在并发时能够正确执行，也就是说基本数据类型的数值或者false赋值、volatile和Atomic* 一起使用（缓存一致性问题 指令重排序问题）

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

15. 笔试题（多线程）

  现在有5个程序员，现在有3个键盘以及3个鼠标。每个程序员需要领到1个键盘以及1个鼠标才能工作，没有领导鼠标或者键盘的程序员会等待。工作完成之后会归还键盘以及鼠标，然后重复领鼠标和键盘去工作。要求尽可能让每个程序员都能够工作和休息（不会出现某个程序员一直在工作，也不会出现某个程序员一直在休息）
  
15. [ThreadLocal原理](https://zhuanlan.zhihu.com/p/150682678)和应用

15. [InheritableThreadLocal原理](https://zhuanlan.zhihu.com/p/101780720) 和 [解决办法](https://www.jianshu.com/p/29f4034f4250)

15. [ThreadLocal-hash冲突与内存泄漏](https://blog.csdn.net/Summer_And_Opencv/article/details/104632272)

15. [如何确保三个线程顺序执行？](https://blog.csdn.net/Evankaka/article/details/80800081)

15. [CompletableFuture](https://juejin.cn/post/6844904195162636295) 男女赛项目

  ```java
     GenderRankVo vo = new GenderRankVo();
      try {
        Map<SexEnum, CompletableFuture<List<StarRankItem>>> futureMap = new ConcurrentHashMap<>();
        for (SexEnum sex : SexEnum.values()) {
          CompletableFuture<List<StarRankItem>> future = CompletableFuture.supplyAsync(() ->
              querySexRank(sex, momoid, trackId, offset, size), ThreadExecuterUtil.genderRankExecutor);
          futureMap.put(sex, future);
        }
        CompletableFuture.allOf(futureMap.values().toArray(new CompletableFuture[futureMap.values().size()])).join();
  
        for (Entry<SexEnum, CompletableFuture<List<StarRankItem>>> entry : futureMap.entrySet()) {
          SexEnum sex = entry.getKey();
          if (sex == SexEnum.FEMALE) {
            vo.setFemaleLists(entry.getValue().get());
          } else if (sex == SexEnum.MALE) {
            vo.setMaleLists(entry.getValue().get());
          }
        }
      } catch (Exception e) {
        log.error("queryGenderDoubleRank fail", e);
        Monitor.inc(MonitorConstant.queryGenderDoubleRank);
      }
      return vo;
  ```
  
  
  
  
  
  
  
    

## 常见考题

1. [单例模式的五种实现方式](https://www.cnblogs.com/zhaoyan001/p/6365064.html)：饿汉式（线程安全）、懒汉式（线程不安全）、懒汉式( 线程安全，synchronized 同步方法，效率太低)、懒汉式( 线程不安全，synchronized 同步代码块，不可用)、双重检查（ 线程不安全，synchronized 同步代码块，二次检查null)、静态内部类、枚举。

   其中饿汉模式、懒汉模式（synchronized方法）、双重检查、静态内部类、枚举这五种可以用。

   2.[DCL](https://blog.csdn.net/qiyei2009/article/details/71813069)
   
   

## linux 命令常见面试题

1. [基础命令](https://blog.csdn.net/weixin_38429587/article/details/79110588)

   




## JVM

1. [JVM精讲](https://www.cnblogs.com/jmcui/category/1503029.html)

1. [**新生代** 老年代 永生代](https://zhuanlan.zhihu.com/p/25539690)

2. [gc算法：](https://www.cnblogs.com/ityouknow/p/5614961.html) **根搜索算法**、**标记 - 清除算法**、**复制算法**、**标记 - 整理算法**

3. **[垃圾回收器](https://www.cnblogs.com/ityouknow/p/5614961.html)**：新生代：**Serial**、**ParNew**、**ParallelScavenge**（优先吞吐量）老生代:**SerialOld**、**ParallelOld**、**CMS （-XX:+UseConcMarkSweepGC 优**响应时间**）**

   其中新生代使用复制算法、老生代使用标记-整理算法，除了CMS（ 标记-清理）

   只有Serial、ParNew 和CMS可以一起使用。

   线上实用的基本上市ParNew + CMS

4. [jvm的内存分布](https://www.cnblogs.com/wtzbk/p/7985156.html?clicktime=1573004363&enterid=1573004363)（看书）

5. [什么时候进行gc ](https://www.zhihu.com/question/41922036/answer/154212925)

6. [G1算法](https://www.cnblogs.com/ityouknow/p/5614961.html) G1[总结 ](https://blog.csdn.net/zy1994hyq/article/details/102495471) [G1和CMS区别](https://zhuanlan.zhihu.com/p/126296343)

6. [ZGC](https://zhuanlan.zhihu.com/p/105921339) [ZGC和G1的区别](https://tech.meituan.com/2020/08/06/new-zgc-practice-in-meituan.html) 着色指针和读屏障技术，解决了转移过程中准确访问对象的问题

6. [SGC(Shenandoah GC)](https://blog.51cto.com/u_14230003/2435438)

6. [**Zing**](https://blog.csdn.net/21aspnet/article/details/88667880)

7. [JVM内存结构、Java内存模型 、Java对象模型](https://mp.weixin.qq.com/s/i_i3aT48NCPukE_6w9Srng)

8. [什么时候进行Minor GC 和 FULL GC](https://blog.csdn.net/varyall/article/details/82527070)

9. [三色标记法与读写屏障](https://www.cnblogs.com/jmcui/p/14165601.html#_label4)

10. full gc 触发条件有哪些？

   - 在要进行 young gc 的时候，根据之前统计数据发现年轻代平均晋升大小比现在老年代剩余空间要大，那就会触发 full gc。
   - 有永久代的话如果永久代满了也会触发 full gc。
   - 老年代空间不足，大对象直接在老年代申请分配，如果此时老年代空间不足则会触发 full gc。
   - 担保失败即 promotion failure，新生代的 to 区放不下从 eden 和 from 拷贝过来对象，或者新生代对象 gc 年龄到达阈值需要晋升这两种情况，老年代如果放不下的话都会触发 full gc。
   - 执行 System.gc()、jmap -dump 等命令会触发 full gc。

11. [TLAB和PLAB](https://xie.infoq.cn/article/ce5ad283b31a7bfe21ac5c542)

16. [Java 反射为什么会慢？](https://juejin.cn/post/6844903965725818887)

17. [go的gc](https://liangyaopei.github.io/2021/01/02/golang-gc-intro/)

18. [java 1.7 1.8的区别](https://blog.csdn.net/lovely_girl1126/article/details/106806879)

19. [java对象在jvm详情](https://www.cnblogs.com/rickiyang/p/14206724.html)

20. [强引用、软引用、弱引用和虚引用](https://juejin.cn/post/6844903665241686029)

11. 



## java关键类源码

1. ThreadPoolExecutor 类源码分享 afterExecute方法执行后打点





# java Framework

## guava

1. [guava](https://app.yinxiang.com/fx/bda2e8b4-608d-4b67-8d70-840ea5d39576)基础

## EventBus

1. [EventBus源码](https://blog.csdn.net/u014634338/article/details/91340593)






# redis相关

## 知识点

1. redis基本命令  (菜鸟命令 结合im项目看 redis相关知识看)
2. redis 底层数据结构[1](https://www.cnblogs.com/jaycekon/p/6227442.html) [2](https://www.cnblogs.com/jaycekon/p/6277653.html) (原理) *要再看 *在看完数据结构的情况下接着看
3. redis 相关题目 ([基础](https://www.cnblogs.com/jasontec/p/9699242.html))
4. redis rdb 和aof [aof](https://redisbook.readthedocs.io/en/latest/internal/aof.html) [rdb](https://redisbook.readthedocs.io/en/latest/internal/rdb.html) [遇到的问题](https://www.iteye.com/blog/xiaoz5919-2093393)、[SAVE BGSAVE BGREWRITEAOF](https://redisbook.readthedocs.io/en/latest/internal/rdb.html)、[AOF RDB持久化高度概括](https://blog.csdn.net/qq_21688757/article/details/79233490)    ***要再看***
5. [缓存穿透，缓存击穿，缓存雪崩](https://blog.csdn.net/zeb_perfect/article/details/54135506)
5. [布隆过滤器](https://zhuanlan.zhihu.com/p/43263751) [redis bitmap使用](https://www.cnblogs.com/54chensongxia/p/13794391.html)
6. [redis的架构模式](https://www.cnblogs.com/jasontec/p/9699242.html) 单机 主从 [sentinel](https://www.jianshu.com/p/06ab9daf921d)  [proxy](https://juejin.im/post/5c132b076fb9a04a08218eef) [cluster](https://blog.51cto.com/alex4dream/2802508)
7. [Redis集群方案](https://www.cnblogs.com/crazymakercircle/p/14282108.html) Redis cluster [哈希槽](https://blog.csdn.net/z15732621582/article/details/79121213) [一致性hash](https://www.cnblogs.com/lpfuture/p/5796398.html) 取模
8. redis [分布式锁redis 命令](https://blog.csdn.net/lihao21/article/details/49104695)  [分布式锁 java 实现](https://my.oschina.net/dengfuwei/blog/1600681)  (结合cms改版看)
9. [深入浅出Redis-redis底层数据结构（上）](https://www.cnblogs.com/jaycekon/p/6227442.html) [深入浅出Redis-redis底层数据结构（下）](https://www.cnblogs.com/jaycekon/p/6277653.html)
9. [redis 五大数据类型实现](https://www.cnblogs.com/ysocean/p/9102811.html#_label5)
10. [底层数据结构](https://blog.csdn.net/qq_36642340/article/details/81020477)
10. [object idletime 命令不准问题](https://segmentfault.com/a/1190000023642663)
10. [redis脑裂](https://www.xhyonline.com/?p=1171) [详细](https://blog.f-fox.com/2020/12/11/redis%E9%9B%86%E7%BE%A4%E8%84%91%E8%A3%82%E5%88%86%E6%9E%90/)
10. [redis一致性问题](https://blog.csdn.net/m0_45406092/article/details/117175920)
10. [分布式锁Redlock处理redis一致性问题](https://blog.csdn.net/hh1sdfsf56456/article/details/79474434)
10. [zskiplist实现](https://blog.csdn.net/riemann_/article/details/116901500) [插入](https://segmentfault.com/a/1190000022320734)

# java架构相关

1. [Apache Commons Pool池化技术](https://zhuanlan.zhihu.com/p/415174080)

## 大数据算法相关

1. [两个大文件中找出共同记录](https://blog.csdn.net/u011389515/article/details/80526971)

 

## 项目实战

1. [redis cluster 线上运维](https://blog.csdn.net/AlbertFly/article/details/80360471) [sentinel集群切换](https://static.app.yinxiang.com/embedded-web/profile/#/join?guid=2668aee3-9af5-42fb-b5b3-990d23179e25&channel=copylink&shardId=s57&ownerId=11397930)
2. [Redis bitmap 使用](https://www.jianshu.com/p/ea087619adc8) [亿万级别使用](https://blog.csdn.net/u011957758/article/details/74783347)


# mysql相关

1. [MySQL的四种事务隔离级别](https://www.cnblogs.com/huanongying/p/7021555.html)

   读未提交ru 读已提交rc 可重复读rr  串行化s

2. [MySQL(Innodb)索引的原理](https://www.cnblogs.com/rjzheng/p/9915754.html)

3. [记录锁，间隙锁，next-key锁](https://blog.csdn.net/qq_39751320/article/details/106299388) [图](https://www.jianshu.com/p/bf862c37c4c9)

4. [mysql/innoDB中，乐观锁，悲观锁，共享锁，排他锁，行锁，表锁，死锁概念的理解](https://segmentfault.com/a/1190000015815061)

5. [Left on/right on](https://blog.csdn.net/qq_35101027/article/details/78288279) [left join和inner join的效率对比](https://blog.csdn.net/LJFPHP/article/details/88635755)

6. [索引优化](https://www.jianshu.com/p/3ffb938a2622)

7. [Mysql中myisam和innodb的区别](http://blog.itpub.net/21374452/viewspace-2136284/)

8. [**普通索引**，**回表**，**索引覆盖**](https://www.jianshu.com/p/8991cbca3854)

9. [可重复读和读已提交原理](https://cloud.tencent.com/developer/article/1811584)

10. 左匹配原则

11. [MVCC](https://www.modb.pro/db/75331)

12. [B-/+/*树，为什么mysql用B+](https://www.jianshu.com/p/ace3cd6526c4)

8. [分库分表](https://tech.meituan.com/2016/11/18/dianping-order-db-sharding.html)



1、从0到1掌握mysql的索引系统

2、索引系统中数据结构的抉择

3、索引的分类及应用场景

4、不同存储引擎索引的区别及数据存储方式

5、索引中隐藏的知识点：索引回表、覆盖索引、索引下推

6、如何创建性能最优的索引

7、索引的优化 



1.[mysql线程池](https://dbaplus.cn/news-11-1989-1.html) [问题](https://app.yinxiang.com/fx/01cd837d-e01c-40e1-a551-51ab0471e19f)

​				 						 		



# spring 相关

##spring

1.[spring生命周期](https://juejin.cn/post/6844904065457979405)

2.[获得**ApplicationContext**的方法](https://www.cnblogs.com/wangcp-2014/p/8126187.html)

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



## spring boot starter

1. [Spring starter使用](https://www.jianshu.com/p/30ce49fc2f25) [原理](https://blog.csdn.net/ruoshui77/article/details/112258495)
2. 常用注解[@Order](https://www.cnblogs.com/satire/p/15094089.html) [@Primary](https://blog.csdn.net/u013400939/article/details/52953804)



# netty参数

1. [ChannelOption参数详解](https://www.jianshu.com/p/975b30171352)

2. ChannelOption.SO_BACKLOG  ChannelOption.TCP_NODELAY ALLOW_HALF_CLOSURE

3. [nettty调参](https://www.cnblogs.com/cfas/p/10422108.html)

4. [编解码](https://www.cnblogs.com/qdhxhz/p/10245936.html)

   FixedLengthFrameDecoder 定长协议解码器

   LineBasedFrameDecoder 行分隔符解码器，遇到\n或者\r\n

   DelimiterBasedFrameDecoder 分隔符解码器

   | ClassName                                                    | 解释                           |
   | ------------------------------------------------------------ | ------------------------------ |
   | FixedLengthFrameDecoder                                      | 定长协议解码器                 |
   | LineBasedFrameDecoder                                        | 行分隔符解码器，遇到\n或者\r\n |
   | DelimiterBasedFrameDecoder                                   | 分隔符解码器                   |
   | [LengthFieldBasedFrameDecoder](https://www.cnblogs.com/java-chen-hao/p/11571229.html) | 长度编码解码器                 |
   | JsonObjectDecoder                                            | json格式解码器                 |
   |                                                              |                                |

5. https://www.jianshu.com/p/a618adef427c

6. handler

   | ClassName                                                    | 解释     |
   | ------------------------------------------------------------ | -------- |
   | [IdleStateHandler](https://www.cnblogs.com/xuwujing/p/7637265.html) | 心跳机制 |
   | ReadTimeoutHandler                                           |          |
   |                                                              |          |
   |                                                              |          |

7. [netty启动参数 ](https://www.jianshu.com/p/0bff7c020af2)[详细解释](https://www.liaoxuefeng.com/discuss/1279869501571105/1450880018677794)

8. [reuseaddr和reuseport](https://www.jianshu.com/p/9cc2b5b9ad4d)

# kafka 相关

1. kafka 如何做到

   - 高吞吐量、低延时；

     1.批处理（提高吞吐量）

     2.![image-20220518223341570](/Users/momo/Library/Application Support/typora-user-images/image-20220518223341570.png)

     3.sendfile和零拷贝

      a.用内核驱动程序处理IO数据，不需要上下文切换，节省内核缓冲区和用户态程序缓冲区的数据拷贝

      b.使用直接储存访问技术（DMA)，避免OS内核缓冲区之间的数据拷贝

     ![image-20220518224324481](/Users/momo/Library/Application Support/typora-user-images/image-20220518224324481.png)

      ![image-20220518224345514](/Users/momo/Library/Application Support/typora-user-images/image-20220518224345514.png)

   - 消息持久化

   - 负载均衡和故障转移

   - 伸缩性

2. kakfa topic-partition-message

3. 怎么做数据恢复的？数据会不会漏？

4. [kafka consumer两种消费方式](https://www.jianshu.com/p/0a05633978f0)

5. [TimingWheel 时间轮详解](https://blog.csdn.net/u013332124/article/details/82119144)

6. [kafka语义](https://blog.csdn.net/laojiaqi/article/details/79034798)

7. kafka延迟（深入理解Kafka核心设计与实践）

8. [kafka面试点](https://www.bilibili.com/read/cv11525238) [大厂经常问](https://zhuanlan.zhihu.com/p/389939447)

9. acks

10. consumer group P2P 模式和广播模式

11. rebalance

    ![image-20220710210941957](/Users/momo/Library/Application Support/typora-user-images/image-20220710210941957.png)

# RocketMq

1. [Kakfa和RocketMq的区别](https://blog.csdn.net/shijinghan1126/article/details/104724407) 
2. [RocketMq如何做到消息不可丢](https://zhuanlan.zhihu.com/p/465112826)
2. [Kafka和RocketMQ实现原理对比](https://mp.weixin.qq.com/s/kme1N1VH5enXpKQ52V6Fbg)
2. Mq做定时任务

# zk相关：

1. [zk面试题目](https://segmentfault.com/a/1190000014479433)
2. [Zookeeper Curator 事件监听 ](https://www.cnblogs.com/crazymakercircle/p/10228385.html)
3. Curator使用[流式风格](http://en.wikipedia.org/wiki/Fluent_interface)
4. Zk的选举算法：basic paxos  fast paxos（系统默认）
5. [zk的主从如何同步，如何主从选举、如何知道集群机器掉线](https://segmentfault.com/a/1190000014479433)
6. zk集群的数据同步 （*写主还是写任意）*
7. [Zookeeper实现分布式锁（保持独占，控制时序），分布式队列](https://blog.nowcoder.net/n/9ff38ae6af90475ea34f4236dd82859c?from=nowcoder_improve)

#大数据相关

## hadoop架构
   hive 看标签，自己本地搭过

## hbase
live-im使用过



## [cassandra](https://developer.aliyun.com/article/718156)

## flink
sunwell使用

##es
live-log和recommend-moniter使用过







# 分布式相关
1. [分布式事务](http://seata.io/zh-cn/docs/overview/what-is-seata.html)

2. [CAP](https://www.cnblogs.com/duanxz/p/5229352.html)

3. 分布式锁实现的方式 redis zk

4. [负载均衡算法及其代码实现](https://mp.weixin.qq.com/s/JvpLtfcx5Fv0sY3w2fH83A?)

   **轮询（Round Robin）法**

   **随机（Random）法**

   **源地址哈希（Hash）法**

   **加权轮询（Weight Round Robin）法**

   **加权随机（Weight Random）法**

   **最小连接数（Least Connections）法**

4. [Paxos、Raft、ZAB、Gossip分布式一致性算法](https://zhuanlan.zhihu.com/p/130332285)


# 系统设计:
1.[近8小时点击量最大的文章前100名]( https://juejin.im/post/5abcd6a0f265da23961279c8)  [Counter服务](https://xumc.github.io/blog/2019/11/23/counter-in-advertising)

2.[千万级别贡献榜设计](https://blog.csdn.net/micro_hz/article/details/110919019)

3.A文件有30亿个QQ号码，B文件有40亿个QQ号码，求A文件和B文件中QQ号码的交集，内存大小限制为1GB.(腾讯终面)

bitmap HyperLogLog

4.[短网址域名系统](https://hufangyun.com/2017/short-url/) [系统架构](https://blog.51cto.com/u_10180290/3226500)
5.[分布式唯一序列号生成服务](https://blog.csdn.net/Abysscarry/article/details/80445581)

[时间回拨问题处理](https://blog.csdn.net/qq_26222859/article/details/123689230)

6.zset做事件处理器 连屏pk和星光pk，setnx加锁

7.[缓存击穿](https://blog.csdn.net/zeb_perfect/article/details/54135506) 加锁 缓存租约
8.[分页重复问题，按timestap做分页](https://blog.csdn.net/jack85986370/article/details/51483872)

9.微信红包系统（并发，库存和红包裂变算法）

10.im在线人数（不是简单的kafka消费，看im的实现）

11.[京东秒杀架构升级优化实践](https://mp.weixin.qq.com/s/bo46q8ohuk78fqXJTaQavQ)

13[.im go的长连接gc问题](https://cloud.tencent.com/developer/article/1069321)

14.[巧用 Bitmap 实现亿级数据统计](https://segmentfault.com/a/1190000040177140)

15. [Feed服务](https://mp.weixin.qq.com/s?__biz=MzI4MTY5NTk4Ng==&mid=2247489693&idx=1&sn=b3138663029f41744203acf174725feb&chksm=eba41b00dcd39216beb85491de7877b91ffd2e4b85562e7ae38d90a64cb78b0142b1ff477fd1&scene=27#wechat_redirect)

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




## 猎头经验
1.数据结构
2、梳理业务及落地（仔细）
3、简历中写到的技术点，要回顾

一面：考察基础知识；介绍做的业务，考察业务中用到的技术深度；一道算法题，看代码风格，能做出来算加分项（刷一周的算法可以使思维活跃）
二面：二面面试官会跟一面面试官协商，考察一面表现薄弱的部分（如果基础好算法弱，二面会考算法；如果算法好基础弱，二面着重考基础）给一道设计题
三面：业务负责人直接面，考察综合能力，通过率较高

一面：
【上海抖音】
1.Jvm堆和栈的区别

2.Jvm年轻代垃圾回收算法

3.Mysql聚簇索引和非聚簇索引的区别

4.Redis key过期的实现

5.Mq如何保证消费有且只有一次

6.网站打不开了怎么排查问题
算法题是链表操作
【上海教育中台】

1. 为啥去年没接offer
2. 项目中数据库选型，mysql聚集和非聚集索引
3. 如何看有没有用上索引，如果where里写了条件但还是没用上索引可能是什么场景？
4. 介绍下NIO，操作系统底层是什么，详解select、poll、epoll区别
5. java线程池参数每个的作用
6. 介绍下你做的几个项目，最有技术含量的详细说下（其实都没有技术含量）
7. 系统设计题：10亿视频、平均50弹幕（有热点）、20亿用户，做到：视频弹幕加载、视频任意位置拖动后加载、用户发的所有弹幕浏览。读多写少
  降低延迟    videoID  offset 内容
   进阶1：考虑热点数据
   进阶2：写变多，读写比变为7:3
8. 算法题：一个长字符串，一个不重复的字符数组。找到一个子串，内容与数组相同（顺序可不同）
   要求：时间复杂度O(N)，且不用任何额外数据结构，数组也不能开
   【杭州商业化广告】
   blockingqueue 
   1、大小固定 
   2、多线程 
   3、支持泛型 
   put、get方法
   算法题：给定一个数组代表股票每天的价格，请问只能买卖一次的情况下，最大化利润是多少？
   输入: {100, 80, 120, 130, 70, 60, 100, 125} 
   输出:65（60 买进，125 卖出）
   【上海广告创意中心】
   1.介绍项目。
   2.Redis中value过大会造成什么问题？为什么？
   3.LRU  怎样实现，怎样优化，局部性原理
   4.MySQL联合索引，怎样不回表？
   5.算法：岛屿问题 （图的遍历）
   【杭州商业化广告】
   1.秒杀系统设计
   2.问了下AOP原理和应用
   算法题：田忌赛马
   【北京商业化广告】
   1.保护系统，限流，令牌桶。
   2.数据库延迟1分钟原因。
   3.cms垃圾回收器可回收浮动垃圾。
   4.新生代存活的对象如何处理。
   5.hashmap原理。
   算法题： 搬家 远亲不如近邻
   输入居民个数，搬家方案，居民位置，方案
   输入：3, 2 [2, 4, 7],[5, 8]
   输出：[1, 1]
   搬到5的位置上，距离最近的居民是4，距离为1
   搬到8的位置上，距离最近的居民是7，距离为1
   【杭州IES互娱】
   1.hashmap的原理，
   2.resize的系列，0.75这个值怎么来的。
   3.redis的数据结构，zset的实现，为什么用的跳表不是红黑树。
   4.http请求的整个链路
   算法题：链表重排序，基数位元素升序，偶数位降序。
   【北京IES互娱】
   1.如何实现并发调用多个RPC接口？
   2.IO多路复用？select/poll/epoll的区别？
   3.netty的NIO实现机制
   4.redis
   5.jvm垃圾回收算法
   算法题：二叉树按层遍历，偶数层倒序
   【杭州商业化广告】
   1.301，302区别
   2.Mysql checkpoint作用
   3.Select和epoll区别
   4.Redis rehash过程
   5.Redis集群添加key的定位算法
   6.Cms有几次stop the world
   7.Rocket架构是什么
   8.一道sql题，出现过2次及以上相同名字的人的名字
   算法题：一道算法题，最大子数组，子数组可以组成顺子，求最大子数组长度，整数数组，比如31254637
   子数组为125463，可以组成123456顺子
   【上海教育中台】
   1.分布式锁
   2.多线程
   3.消息队列保证消息有序
   算法题：1-26对应a-z字母，随机写一个数字，输出所有的组合可能情况
   算法题：两个链表融合成一个，并排序

二面：

【上海教育中台】
1. 分库分表方案，淘宝订单场景，能按卖家ID+买家ID+订单ID查询
2. 算法题：手写快排，能跑
3. 算法题：判断对称二叉树
4. 聚集和非聚集索引，实现区别
5. kafka如何保证消息有序
6. 一致性哈希
7. 缓存穿透怎么处理
8. 介绍一个最有亮点的项目
9. TIME_WAIT中的2msl，为什么是这个时间
10. https建立连接过程
11. 为啥去年没接offer
【杭州商业化广告】
List<10000> 
10个线程去执行 
10个线程都完成了，在进行后续的动作
1. 写一个队列，然后大小固定
2. 写一个多线程消费，且保证所有线程都处理完成才可以
【上海广告创意中心】
1.项目
2.MySQL联合索引
3.谈谈对Kafka的理解，与其他中间件的区别，怎样保证数据一致性？
4.手撕堵塞队列、堆排序、第K大的数字，时间复杂度是多少？为什么？
5.介绍java线程池的类型、主要参数、工作原理。
6.Synchronized 可以嵌套使用吗
【北京商业化广告】
1.mysql主从复制，原理，
2.binglog日志格式 
3.redis事务,分布式锁，线程模型，持久化
4.hashmap优化，concurrenthashmap
5.volitale
6.单例模式
7.mutex和pipline
8.二分查找
【杭州商业化广告】
1.先聊项目
2.Redis压缩用什么算法
3.线上表增加列有什么问题？如果加临时表增量数据如何同步？
4.联合索引a+b+c，如果where a=10 and b<10 and c=10有没有用到索引？
5.自旋锁是什么？为什么要用？用户态和内核态切换要做什么？上下文切换主要做了什么？
6.任意精度的延时队列怎么设计？堆的插入时间复杂度是多少？
7.垃圾收集器怎么工作的？
8.a方法调用b方法是做了什么？b方法的返回值存储在哪里？
算法题：找出字符串中没有重复字符的最长子串的长度

三面：
【上海教育中台】
1. 正则：写一个手机号的正则表达式，13开头，11位数
2. 算法题：单链表，每N个一组进行翻转
3. 系统设计：微博点赞场景，能查用户点赞记录、不能重复点赞、能查当天热榜Top10
4. mq的高吞吐量咋做到的
5. TCP几次握手、几次挥手、TIME_WAIT在什么场景出现
6. 讲下DNS劫持
7. 未来职业规划
【上海广告创意中心】
1.算法：大数减法
2.分布式事务
3.AOP的实现原理，怎样实现动态代理
4.最有挑战性的事是什么
5.有什么问题要问？
【北京抖音】
1.做过的项目中最有挑战、难度最大的是什么，详细介绍
2.学习新领域、新知识的方法
3.服务治理都有哪些模块
4.注册中心的原理
5.为什么配置中心也属于服务治理
6.链路监控的原理，并发调用多个下游服务怎么区分这些请求
7.全链路压测怎么做？遇到了什么问题
8.算法：将一颗二叉树转化成单链表，将每个节点的左子树插入该节点和其右子树之间，左子指向Null
9.设计题：设计直播送礼系统，观众给主播送礼，相当于余额的扣除/增加。并发量大怎么办？了解消息队列的实现吗？同时有多个主播在做直播，怎么从消息队列中读取信息？写消息队列失败怎么办，在哪里做重试？没有明确失败，只是消息超时怎么办？最终写数据库失败怎么办？
【杭州抖音】
1.mysql事物的特性，实现方式。
2.设计分布式限流
3.设计微信红包系统
4.设计题：设计直播送礼系统，观众给主播送礼，相当于余额的扣除/增加。并发量大怎么办？了解消息队列的实现吗？同时有多个主播在做直播，怎么从消息队列中读取信息？写消息队列失败怎么办，在哪里做重试？没有明确失败，只是消息超时怎么办？最终写数据库失败怎么办？
5.编程是对一个链表，每k个节点进行一次翻转

HR面：
1.为什么想换工作
2.平时怎样学习的？
3.手里的其他offer，预期的待遇
4.其余就是聊天，介绍字节的文化





1.redis 的基本数据结构
2.用堆排序，m 个排一次，然后补充数据，最后得到结果
3.m 个有序数组，每个数组长度为 n，将 m 个数组生成 1 个有序数组，如何做？

1.数据库不用b+树还可用什么数据结构？
2.跳表如何判断这个数据插在哪里？跳表和 b+树比哪个效率更高？
3.什么情况下不使用索引？
4.http 2.0 优点？
5.外部调用为什么不用rpc 而用http 协议？http 协议有什么不可替代性？





https://www.jianshu.com/p/d6e9b1c211dd

# 项目相关：

# 工具相关：
1.[git flow](https://www.ruanyifeng.com/blog/2015/12/git-workflow.html) 

2.[ci cd](https://www.redhat.com/zh/topics/devops/what-is-ci-cd)

3.[异地多活](http://kaito-kidd.com/2021/10/15/what-is-the-multi-site-high-availability-design/)
