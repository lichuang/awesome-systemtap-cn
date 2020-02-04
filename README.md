# 目录

* [教程类](#教程类)
* [手册类](#手册类)
* [实例类](#实例类)
* [使用技巧类](#使用技巧类)
* [实用工具类](#实用工具类)
* [其他](#其他)

# 教程类
* [通过实例快速入门Systemtap](https://www.codedump.info/post/20200128-systemtap-by-example/)：我自己学习过程中的一个学习笔记，通过例子展示用法。
* [金九讲SystemTap使用技巧](https://zhuanlan.zhihu.com/p/28680568)：阿里技术专家的教程，也是很不错的。
* [Using SystemTap by Brendan](http://dtrace.org/blogs/brendan/2011/10/15/using-systemtap/)：Brendan在2011年写的介绍博客。
* [Systemtap tutorial](https://sourceware.org/systemtap/tutorial.pdf)：官方教程。
* [SystemTap Beginners Guide](https://sourceware.org/systemtap/SystemTap_Beginners_Guide/)：官方的新手入门指南。

# 手册类
* [SystemTap Language Reference](https://sourceware.org/systemtap/langref.pdf)：官方的Systemtap语言参考手册。
* [SystemTap Tapset Reference Manual](https://sourceware.org/systemtap/tapsets/)：tapset是Systemtap安装后自带的脚本库，这份文档是tapset的参考手册。
* [Systemtap man Manual](https://sourceware.org/systemtap/man/)：Systemtap相关组件在线的man手册文档。

# 实例类
* [官方文档-Systemtap examples](https://sourceware.org/systemtap/examples/)：systemtap自带了一个examples目录，里面有关于进程、profile、内存、IO等的大量systemtap脚本例子，是学习systemtap的绝佳示范。
* [Monitoring MySQL with DTrace/SystemTap](https://www.slideshare.net/posullivan/monitoring-mysql-with-dtracesystemtap)：使用Systemtap跟踪Mysql性能的pdf。
* [使用动态跟踪技术SystemTap监控MySQL、Oracle性能](http://tech.it168.com/a2018/0808/5005/000005005369.shtml)

# 使用技巧类

* [yufeng的博客](http://blog.yufeng.info/archives/category/tools)：yufeng是内地最早介绍systemtap相关技术的人，其早期博客有不少systemtap使用技巧。
* [使用SystemTap给系统调用注入错误 — 源代码](https://lrita.github.io/2017/06/27/systemtap-inject-syscall-error/)：通过systemtap向系统调用注入错误，来模拟一些异常的情况，这个很实用。
* [systemtap 修改系统调用参数](https://tcler.github.io/2017/09/11/systemtap-modify-syscall-parameters/)：同上。

# 实用工具类

* [openresty-systemtap-toolkit](https://github.com/openresty/openresty-systemtap-toolkit)：agentzh当时为Openresty写的一些systemtap脚本工具集，使用Perl脚本编写，其中部分脚本不止能诊断Openresty，还可以诊断其他进程。目前已经停止更新，转向了动态跟踪的XRay平台。
* [tcpdive](https://github.com/fastos/tcpdive)：看项目描述是提供了一堆对TCP网络进行profile的脚本工具集合，这些脚本都是使用systemtap编写的，可以作为工具或者实例来参考。另外还自带了一份[systemtap教程](https://www.kancloud.cn/digest/tcpdive/120062)，略粗糙。
* [systemtap-script](https://github.com/soarpenguin/systemtap-script)：useful systemtap script，但是看提交时间也是常年不更新了，作为例子参考吧。

# 其他
* [动态追踪技术漫谈](https://openresty.org/posts/dynamic-tracing/)：动态追踪（dynamic tracing）是一种技术，特指对线上还在运行的程序进行调试、跟踪的技术，而Systemtap是Linux平台下进行动态跟踪的常见工具，这篇文章介绍什么是动态跟踪技术。
* [brendangregg的博客](http://www.brendangregg.com/)：solaris平台下动态跟踪工具Dtrace的作者，博客中讨论了大量关于动态跟踪技术、profile技术的内容。