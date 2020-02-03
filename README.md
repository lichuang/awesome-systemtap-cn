# 教程类
* [通过实例快速入门Systemtap](https://www.codedump.info/post/20200128-systemtap-by-example/)：我自己学习过程中的一个学习笔记，通过例子展示用法。
* [金九讲SystemTap使用技巧](https://zhuanlan.zhihu.com/p/28680568)：阿里技术专家的教程，也是很不错的。
* [Using SystemTap by Brendan](http://dtrace.org/blogs/brendan/2011/10/15/using-systemtap/)：Brendan在2011年写的介绍博客。
* [Systemtap tutorial](https://sourceware.org/systemtap/tutorial.pdf)：官方教程。
* [SystemTap Beginners Guide](https://sourceware.org/systemtap/SystemTap_Beginners_Guide/)：官方的新手入门指南。

# 手册类
* [SystemTap Language Reference](https://sourceware.org/systemtap/langref.pdf)：官方的Systemtap语言参考手册。
* [SystemTap Tapset Reference Manual](https://sourceware.org/systemtap/tapsets/)：tapset是Systemtap安装后自带的脚本库，这份文档是tapset的参考手册。

# 实例类
* [官方文档-Systemtap examples](https://sourceware.org/systemtap/examples/)：systemtap自带了一个examples目录，里面有关于进程、profile、内存、IO等的大量systemtap脚本例子，是学习systemtap的绝佳示范。
* [Monitoring MySQL with DTrace/SystemTap](https://www.slideshare.net/posullivan/monitoring-mysql-with-dtracesystemtap)：使用Systemtap跟踪Mysql性能的pdf。

# 使用技巧类

* [yufeng的博客](http://blog.yufeng.info/archives/category/tools)：yufeng是内地最早介绍systemtap相关技术的人，其早期博客有不少systemtap使用技巧。

# 实用工具类

* [openresty-systemtap-toolkit](https://github.com/openresty/openresty-systemtap-toolkit)：agentzh当时为Openresty写的一些systemtap脚本工具集，使用Perl脚本编写，其中部分脚本不止能诊断Openresty，还可以诊断其他进程。目前已经停止更新，转向了动态跟踪的XRay平台。

# 其他
* [动态追踪技术漫谈](https://openresty.org/posts/dynamic-tracing/)：动态追踪（dynamic tracing）是一种技术，特指对线上还在运行的程序进行调试、跟踪的技术，而Systemtap是Linux平台下进行动态跟踪的常见工具，这篇文章介绍什么是动态跟踪技术。