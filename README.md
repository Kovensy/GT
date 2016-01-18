什么是GT？
------------------------------------------

GT（随身调）是APP的随身调试平台，它是直接运行在手机上的“集成调试环境”(IDTE, Integrated Debug Environment)。

利用GT，仅凭一部手机，无需连接电脑，即可对APP进行快速的性能测试(CPU、内存、流量、电量、帧率/流畅度等等)、开发日志的查看、Crash日志查看、网络数据包的抓取、APP内部参数的调试、真机代码耗时统计等。

如果您觉得GT提供的功能还不够满足您的需要，您还可以利用GT提供的基础API自行开发有特殊功能的GT插件，帮助您解决更加复杂的APP调试问题。

详情请见官网：http://gt.qq.com


如何使用？
------------------------------------------
GT支持iOS和Android两个手机平台，其中：

iOS版是一个Framework包，必须嵌入APP工程，编译出带GT的APP才能使用；iPhone和iPad应用都能支持。

Android版由一个可直接安装的GT控制台APP和GT SDK组成，GT控制台可以独立安装使用，SDK需嵌入被调试的应用、并利用GT控制台进行信息展示和参数修改。


源代码说明
------------------------------------------
android是Android版本GT。
ios是iOS版本GT。