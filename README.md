# JVM-study
JVM的重要性毋庸置疑，可以毫不夸张的说Java虚拟机是整个Java平台的基石。 JVM方面的知识，也一直是BAT等大厂面试考核的重点。特别是JVM调优，故障排查性能调优，你知道该从哪些方面入手吗？ 

此专栏结合自己对JVM的理解，从java运行时数据区、java内存模型(JMM)、什么是垃圾回收，垃圾回收算法、垃圾收集器、内存分配与回收策略等，也会介绍安全点、安全区域等知识点，还有什么是“卡带”？ 相信学习完专栏，在面试时被问到JVM，你定能跟面试官侃侃而谈，话聊人生！

关于JVM的历史以及重要性我就不做介绍，网上能搜到一大堆。我们就直接上干货，希望能最简单直白语言来深入浅出，一步步揭开JVM的面纱。

## 本专栏将分为如下几个大模块进行分析：
1. 开篇介绍
2. Java运行时数据区。
3. 什么是垃圾回收？
4. 常用垃圾回收算法及HotSpot的算法实现。
5. 垃圾收集器。
6. 内存分配与回收策略。此模块也会延展一些内存回收时的**坑**。
7. Java内存模型（JMM）。
8. 头脑风暴（即JVM必备题）。

专栏将会围绕如下脑图进行展开（**此脑图会持续进行完善**）：
![JVM _2_.png](https://i.loli.net/2019/08/19/Vdh6brKZaNRDtkx.png)

>此脑图会持续维护并进行完善，高清无码大图可扫描下方二维码，在微信公众号（猿人谷）输入关键字“jvm”即可。

**鬼知道我看了多少相关的书籍和博客，都没找到适合我的，不得不自己动手撸几篇，请叫我知识的搬运工**。 此专栏算是我在学习Java虚拟机的读书笔记及经验总结，在小伙伴们阅读专栏的过程中，如有哪一块的知识想了解，可以留言告知。

>参考书籍：《深入理解Java虚拟机》、《Java虚拟机规范》（Java SE 8版）、《HotSpot实战》。

![猿人谷.jpeg](https://i.loli.net/2019/08/20/dBJZkfcAMsUnx1w.jpg)


