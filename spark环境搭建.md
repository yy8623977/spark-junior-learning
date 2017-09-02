# 章节1: spark环境搭建  
  
## 课时1: spark概述  
  
### 大数据技术  
- hadoop: 能为你的数据储存项目提供所需要的HDFS、YARN基础架构,并且运行主要的大数据服务和应用程序  
- spark: 基于内存,栈式的解决方案,更适用于需要迭代式计算  
  
### spark应用框架  
![spark应用框架](http://a3.qpic.cn/psb?/V13TxjFt0sc2rb/8WYMt4WSXs1s4aRIKBcvp0n1eou9Ef*7u73v0Fu6hCE!/b/dPIAAAAAAAAA&bo=BAI1AQAAAAADBxA!&rf=viewer_4)
  
### spark和hadoop对比  
- 性能: spark将中间结果保存到内存,当数据大小适于读入内存,尤其是在专用集群上,spark会更好---hadoop适用于数据不能全部读入内存的情况,同时它还可以同其它服务同时运行  
- 兼容性: spark和hadoop具有相同的数据类型和数据源的兼容性  
- 容错: hadoop比spark稍微好一点  
- 成本: spark基于高的cpu和内存配置,而hadoop面向的是普通PC,如果是非常大的数据,倾向于hadoop,因为硬盘便宜  
  
## 课时2: spark的编程语言介绍  
  
### spark的编程语言  
spark支持scala,java,python,R语言的API操作  
  
### scala语言  
scala是一门多范式的编程语言,能实现可伸缩的语言、并集成面向对象编程和函数式编程的各种特性  
**多范式**  
scala支持使用多种不同的编程方法,如面向过程,面向对象,泛型,函数式等设计方法
**类似java**  
scala是基于java虚拟机,所有的scala代码,都需要经过编译为字节码,然后交由java虚拟机来运行,scala可以任意调用java代码,实现无缝对接  
### scala基础语法  

  
