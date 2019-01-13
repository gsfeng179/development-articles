# 分享一线互联网常用技术与问题解决方案


### DB数据异构
* [Alibaba 数据异构利器Canal](https://github.com/alibaba/canal)
* [美团 DB 数据同步到数据仓库的架构与实践](https://tech.meituan.com/binlog_dw.html)
* [ElasticSearch + Canal 开发千万级的实时搜索系统](https://mp.weixin.qq.com/s/ztVsWqAtO1kT9dFZLW3rZg)
* [Msql-Canal数据库同步](https://mp.weixin.qq.com/s/TwhzVdEIEIGx2Rir_5tG8w)
* ...
###### 源码解读系列
* [Canal源码学习-端木轩](notes/canal_源码解读.md)
* ...

### 分布式
##### 分布式事务
* [分布式事务怎么处理？一文告诉你!](https://mp.weixin.qq.com/s?__biz=MjM5NzMyMjUwMg==&mid=2247484753&idx=1&sn=fe10b3214b402c132d2dfcd44b9429b9&chksm=a6da8f3891ad062eef19a4e09b5565da313207f4cb508dccb934d857a5efce7d21856016d2ae&scene=0#rd)
* [分布式事务的实现原理](https://mp.weixin.qq.com/s?__biz=MzIyNjE4NjI2Nw==&mid=2652561049&idx=1&sn=474130817146891a890454029e02d80a&chksm=f39a3bedc4edb2fbd501ecff2daa7a8ffa5f93d327bf0d434abe7ba8c63568fd959c493bc482&scene=0#rd)
* [聊聊微服务架构及分布式事务解决方案！](https://mp.weixin.qq.com/s?__biz=MzI3ODcxMzQzMw==&mid=2247486512&idx=1&sn=01ce7459e71ffe204025fb66248a0c08&chksm=eb538906dc240010f561e14f4a71f98db2e35eee892523e71456675bdbe30c56b0096433d975&scene=0#rd)
> 连载
>* [初识分布式系统](https://www.hollischuang.com/archives/655)
>* [关于分布式一致性的探究](https://www.hollischuang.com/archives/663)
>* [分布式系统的CAP理论](https://www.hollischuang.com/archives/666)
>* [分布式系统的BASE理论](https://www.hollischuang.com/archives/672)
>* [关于分布式事务、两阶段提交协议、三阶提交协议](https://www.hollischuang.com/archives/681)
>* [深入理解分布式系统的2PC和3PC](https://www.hollischuang.com/archives/1580)
>* [Java中的事务——JDBC事务和JTA事务](https://www.hollischuang.com/archives/1658)
>* [Java中的事务——全局事务与本地事务](https://www.hollischuang.com/archives/1678)
>* [分布式事务解决方案——柔性事务与服务模式](https://www.hollischuang.com/archives/2591)
* [Saga分布式事务解决方案与实践](https://mp.weixin.qq.com/s?__biz=MzI4MTY5NTk4Ng==&mid=2247489026&amp;idx=1&amp;sn=67184a64653164d1c48255e0e87373c8&source=41#wechat_redirect)
* [分布式事务在Sharding-Sphere中的实现](https://mp.weixin.qq.com/s?__biz=MzI4NTA1MDEwNg==&mid=2650769307&idx=1&sn=472840471324f466032aecef2df1be68&chksm=f3f9320ec48ebb18a853a55c5338b21e7a3303f12c68b648d6130cfae7a0fdcde1b72e3f2403&scene=0#rd)
* [漫画：什么是分布式事务？](https://note.youdao.com/share/?id=7d2ac7535fd669a8575cb098824f6b68&type=note#/)
* [从银行转账失败到分布式事务：总结与思考](https://note.youdao.com/share/?id=3ff0b6ad0c6393d3e90493733a8f0a78&type=note#/)
* [浅谈分布式事务](https://note.youdao.com/share/?id=8ffe38ba0b0011a4a55c259c93773c22&type=note#/)
* [聊聊分布式事务，再说说解决方案](http://www.cnblogs.com/savorboard/p/distributed-system-transaction-consistency.html)

* [拜托，面试请不要再问我TCC分布式事务的实现原理！【石杉的架构笔记】](https://mp.weixin.qq.com/s/mIW1_K5fAoa2OlSLdXSHpQ)
* [最终一致性分布式事务如何保障实际生产中99.99%高可用？【石杉的架构笔记】](https://mp.weixin.qq.com/s/yRDUQtVPz5eqCx961xL6nw)
* []()
##### RPC

### 随读
* [网站高并发大流量访问的处理及解决方法](http://mp.weixin.qq.com/s/OMyWg53xBF2_Lk0QYDOWpw)
* [消息队列技术点梳理（思维导图版）](https://mp.weixin.qq.com/s/8btqiyxPY1XhvN2UTqDUxw)
* [MQ消息轨迹](http://mp.weixin.qq.com/s/h3Q8tLUFjta0i14OXiExqQ)
* [聊聊高并发系统之降级特技](http://mp.weixin.qq.com/s/FcPzLkP7n8MVaOnZibGs1w)
* [Java并发原理与JMM](http://mp.weixin.qq.com/s/z057Va1JNNOjTTrnuE9pPg)
* [【系统架构】Web系统大规模并发：电商秒杀与抢购](http://mp.weixin.qq.com/s/zDbcV_vJeBOnAYxK0WEJQQ)
* [spring容器及bean加载机制源码解读](http://mp.weixin.qq.com/s/zRjokN97kBu__mcuEBC_Lg)
* [消息中间件选型分析](http://mp.weixin.qq.com/s/Zwd1USlOCkQvsG96eSwvpg)
* [Spring MVC & Boot & Cloud 技术教程汇总（长期更新）](https://mp.weixin.qq.com/s/qLnHqK6AKCoFHBlPdablxw)
* [【缓存】缓存中常见的4种问题分析以及解决方案](https://blog.csdn.net/zzh920625/article/details/78173099?from=timeline&isappinstalled=0#10006-weixin-1-52626-6b3bffd01fdde4900130bc5a2751b6d1)
* [金丝雀发布、滚动发布、蓝绿发布到底有什么差别？关键点是什么？](http://mp.weixin.qq.com/s/WdCM6cOmjdhAEa6PtviH9A)
* [零基础都秒懂：手把手教你搭建一套微服务框架！](http://mp.weixin.qq.com/s/lokfpgObn6bF7BahARfkfg)
* [大话程序猿眼里的高并发！](http://mp.weixin.qq.com/s/gf_h9IQz-oZ_wxis0yUEHg)
* ...

# [Spring](notes/Spring.md)
* [Spring核心技术原理（1）为什么要有Spring?](https://mp.weixin.qq.com/s/s77m4K272p6qm4VmEDdbCw)
* [Spring核心技术原理（2）为什么要有Spring AOP？](https://mp.weixin.qq.com/s/Jcpp-5dib242nuhizU3dmQ)
* [Spring核心技术原理（3）Spring历史版本变迁和如今的生态帝国](https://mp.weixin.qq.com/s/CoCZlFAKzCNVFqk3w3Pzpg)
* ...
# Java基础
* [漫画：什么是单例模式？（整合版）](http://note.youdao.com/noteshare?id=b45dfc81cca23a69893020a389fcc121&sub=020DE73E0EA1415EBD42884F97A7A40D)
* [深入理解单例模式：静态内部类单例原理](https://blog.csdn.net/mnb65482/article/details/80458571)

# 网络
* [改变世界的TCP/IP协议](https://mp.weixin.qq.com/s/qDHY7r068UTpJnYcJ1Favw)
* ...
# 开源项目源码阅读
* [Sharding-JDBC 源码解析合集](http://www.iocoder.cn/categories/Sharding-JDBC/?mp)
* [MyCAT 源码解析合集](http://www.iocoder.cn/categories/MyCAT/?mp)
* ...

### 码农翻身大佬刘欣文章集锦
* [码农翻身2016全年文章精华](https://mp.weixin.qq.com/s/EjVfk1iOuQUjLfPxt_DJ7Q)
* [码农翻身2017全年文章精华](https://mp.weixin.qq.com/s/cbaR--hlEN37fwTIRNhKaQ)
* ...