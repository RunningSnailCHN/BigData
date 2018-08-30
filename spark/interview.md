# 大数据开发工程师面试题
## 1.spark core
1.1 rdd 特点  
1.2 rdd transform 和action介绍  
1.3 rdd 的action有哪些  
1.4 什么时候发生shuffle

## 2.spark streaming
2.1 如何处理kafka中的offset
## 3.spark sql
 3.1 Hive sql 和 SparkSql 区别  
## 4.其他组件
4.1 namenode 怎么实现高可用性  
4.2 zookeeper 在spark中哪里可以用到  
4.3 使用什么格式存储文件，parquet为什么快 +2

## 5.java/scala
5.1 scala比java好在哪里  
5.2 线程池原理
5.3 hashMap桶的大小，是否是线程安全的

## 6.jvm 
6.1 什么时候发生full GC  
Minor GC触发条件：当Eden区满时，触发Minor GC。

Full GC触发条件：

（1）调用System.gc时，系统建议执行Full GC，但是不必然执行

（2）老年代空间不足

（3）方法区空间不足

（4）通过Minor GC后进入老年代的平均大小大于老年代的可用内存

（5）由Eden区、From Space区向To Space区复制时，对象大小大于To Space可用内存，则把该对象转存到老年代，且老年代的可用内存小于该对象大小  
6.2 jvm 内存模型  
