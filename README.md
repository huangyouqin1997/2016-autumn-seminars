# 哈工大2016秋季学期计算机兴趣小组讨论班计划

讨论班旨在通过聚集对计算机技术抱有学习热情的同学一同学习，起到增进交流、提高学习效率等目的。同时作为一种外部的督促手段，降低挖坑填不上的概率:smirk:

欢迎加入QQ群 288689953 讨论，入群请备注年级和姓名。[Techo讨论贴](https://techo.io/topic/121/)

此 Repo 将作人员统计/进度更新/Slides整理之用。

## 讨论班列表

暂列如下，如果人数较少，将可能取消；如果希望增加讨论班课程，请在QQ群中发起讨论。

- [《深入理解计算机系统》](#csapp) - https://book.douban.com/subject/5333562/
- [《计算机程序的构造与解释》](#sicp) - https://book.douban.com/subject/1148282/
- [C语言](#tcpl)
- [《Intel 汇编语言程序设计》](#assembly-lang)


已取消的讨论班

- Linux操作系统使用
- 操作系统
- 《面向机器学习的神经网络》 - 时隔四年，深度学习鼻祖 Geoffrey Hinton 的[神经网络公开课](https://www.coursera.org/learn/neural-networks)再次登陆 Coursera

如何加入一个讨论班：

1. 加入QQ群
2. Fork 此项目
3. 编辑 `README.md`，在讨论班下添加自己的名字
4. 提交 Pull Request

请务必学会使用 GitHub，如何提交 Pull Request 请参考[这里](https://techo.io/topic/121/2016/3)。

<h2 id="csapp">深入理解计算机系统</h2>

- 参与人员（请按照自己所在校区填写）
  + 一区：叶忠豪、文灏洋、商庆达、汪泽堃、向政鹏、孙颖凯、徐阳、周雄、李秋豪、张霖瑄、马玉坤、张征、江家伟、赵世家
  + 二区：肖浩宇
- 时间地点
  + 时间：暂定周六下午，具体时间待更新
  + 地点：[空白格咖啡店](http://mp.weixin.qq.com/s?__biz=MzI3ODI5MjQ0Nw==&mid=100000031&idx=1&sn=bd5855c94ec7a5a88d5471d0e9b98c35&scene=18)


内容安排

| 章节 | 内容 | 负责人  | 时间   | 地点   |
| ---- | ---- | ---- | ---- | ---- |
| 第1章 + 第2章 | 计算机系统漫游 + 信息的表示与处理 |肖浩宇|      |      |
| 第3章 第1 ~ 7节  | 程序的机器级表示（上） |      |      |      |
| 第3章 第8 ~ 15节 | 程序的机器级表示（下） |      |      |      |
| 第4章 第1 ~ 3节  | Y86的顺序实现（一）  |      |      |      |
| 第4章 第1 ~ 3节  | Y86的顺序实现（二） |      |      |      |
| 第4章 第4 ~ 6节  | Y86的流水线实现|      |      |      |
| 第5章 | 优化程序性能 |      |      |      |
| 第6章 | 存储器层次结构 |      |      |      |
| 第7章 | 链接 |      |      |      |
| 第8章 | 异常控制流 |      |      |      |
| 第9章 第1 ~ 7节  | 虚拟存储器（上） |      |      |      |
| 第9章 第7 ~ 12节 | 虚拟存储器（下） |      |      |      |
| 第10章 | 系统级I/O |商庆达|      |      |
| 第11章 | 网络编程 |叶忠豪|      |      |
| 第12章 | 并发编程 |赵世家|      |      |

<h2 id="sicp">计算机程序的构造与解释</h2>

- 参与人员
  + 一区：李盛秋、李博、张征、赵洋、周雄
  + 二区：王昭为

- 时间地点
  + 时间：暂定周六下午，具体时间待更新
  + 地点：[空白格咖啡店](http://mp.weixin.qq.com/s?__biz=MzI3ODI5MjQ0Nw==&mid=100000031&idx=1&sn=bd5855c94ec7a5a88d5471d0e9b98c35&scene=18)

- 说明
  + SICP讨论班预计无法在1个学期内完成
  + 部分小节可能会占用不止一次讨论的时间

- 参考资源
  + https://github.com/FoOTOo/inftik
  + https://github.com/DeathKing/Learning-SICP

内容安排

| 章节 | 内容 | 负责人 | 时间 | 地点 |
| ---- | ---- | ------ | ---- | ---- |
| 第1章 第1节 | 程序设计的基本元素 |     |      |
| 第1章 第2节 | 过程与他们产生的计算 |     |      |
| 第1章 第3节 | 用高阶函数做抽象 |     |      |
| 第2章 第1节 | 数据抽象导引 |     |      |
| 第2章 第2节 | 层次性数据和闭包性质 |     |      |
| 第2章 第3节 | 符号数据 |     |      |
| 第2章 第4节 | 抽象数据的多重表示 |     |      |
| 第2章 第5节 | 带有通用性操作的系统 |     |      |
| 第3章 第1节 | 赋值和局部状态 |     |      |
| 第3章 第2节 | 求值的环境模型 |     |      |
| 第3章 第3节 | 用变动数据做模拟 |     |      |
| 第3章 第4节 | 并发：时间是一个本质问题 |     |      |
| 第3章 第5节 | 流 |     |      |
| 第4章 第1节 | 元循环求值器 |     |      |
| 第4章 第2节 | Scheme的变形——惰性求值 |     |      |
| 第4章 第3节 | Scheme的变形——非确定性计算 |     |      |
| 第4章 第4节 | 逻辑程序设计算 |     |      |
| 第5章 第1节 | 寄存器机器的设计 |     |      |
| 第5章 第2节 | 一个寄存器机器模拟器 |     |      |
| 第5章 第3节 | 存储分配和废料收集 |     |      |
| 第5章 第4节 | 显式控制的求值器 |     |      |
| 第5章 第5节 | 编译 |     |      |

<h2 id="tcpl">C语言</h2>

- 主要参考书籍
  + [C Primer Plus](https://book.douban.com/subject/1240002/)

- 其他推荐参考书籍
  + [C语言程序设计：现代方法](https://book.douban.com/subject/2280547/)
  + [C程序设计语言](https://book.douban.com/subject/1139336/)

- 参与人员
  + 一区
  + 二区：王世川、阮昱彬、神、白楠、徐琪敏、陈哲、王昭为

- 时间地点
  + 时间：周日下午
  + 地点：二区教室

内容安排

| 章节 | 内容 | 负责人 | 时间 | 地点 |
| ---- | ---- | ---- | ---- | ---- |
| 第1章、第2章 | 概览、C语言概述 |      |      |      |
| 第3章、第4章 | 数据和C、字符串的格式化输入/输出 |      |      |      |
| 第5章、第6章 | 运算符/表达式和语句、 循环 |      |      |      |
| 第7章、第8章 | 分支和跳转、字符的输入和输出  |      |      |      |
| 第9章 | 函数 |      |      |      |
| 第10章 | 数组和指针（一） |      |      |      |
| 第10章 | 数组和指针（二）  |      |      |      |
| 第11章、第12章 | 字符串和字符串函数、存储类 链接和内存管理 |      |      |      |
| 第13章 | 文件的输入和输出  |      |      |      |
| 第14章、第15章 | 结构和其他数据形式、位操作 |      |      |      |
| 第16章 | C预处理器和C库 |      |      |      |
| 第17章 | 高级数据表示 |      |      |      |

<h2 id="assembly-lang">《Intel 汇编语言程序设计》</h2>

- 参与人员
  + 一区：
  + 二区：王世川、阮昱彬、神、肖浩宇、白楠、陈哲

- 时间地点
  + 时间：周日下午
  + 地点：二区教室

内容安排

| 章节   | 内容 | 负责人  | 时间   | 地点   |
| ---- | ---- | ---- | ---- | ---- |
| 第1章、第2章 | 基本概念、IA-32处理器体系结构 |      |      |
| 第3章 | 汇编语言基础 |      |      |
| 第4章 | 数据传送、寻址和算术运算 |      |      |
| 第5章 | 过程 |      |      |
| 第6章 | 条件处理 |      |      |
| 第7章 | 整数算数指令 |      |      |
| 第8章 | 高级过程 |      |      |
| 第9章 | 字符串和数组 |      |      |
| 第10章 | 结构和宏 |      |      |
| 第12章 | 高级语言接口 |      |      |
| 第17章 | 浮点处理和指令编码 |      |      |


