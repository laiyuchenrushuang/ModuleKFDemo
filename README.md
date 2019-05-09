# ModuleKFDemo
最近接触的项目，这种模块化的比较多，不知道里面怎么调用的，今天配置了下模块化的环境，感觉没啥用，哎，项目都是一个人开发，我拿模块干什么。

-----------------------------------------------------------------------------------------------------------------------------


新建项目遇到问题的解决办法：

新建项目时出现这个问题.解决方法有两步如下: 一.将module的 apply plugin: 'com.android.application' 改为 apply plugin: 'com.android.library' 二.删除module的 applicationId ,即下面: defaultConfig { applicationId "xx.xx.xxx" } 即可顺利解决问题
