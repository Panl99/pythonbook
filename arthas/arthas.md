> [https://github.com/alibaba/arthas](https://github.com/alibaba/arthas)  
> [Arthas在线文档](https://arthas.aliyun.com/doc/arthas-tutorials.html?language=cn)  
> [Arthas用户文档](https://arthas.aliyun.com/doc/)  

# 目录
- [Arthas介绍](#Arthas介绍)


[目录](#目录)

# Arthas介绍
`Arthas` 是Alibaba开源的Java诊断工具。

- Arthas可以解决：
    - 这个类从哪个 jar 包加载的？ 为什么会报各种类相关的 Exception？
    - 我改的代码为什么没有执行到？ 难道是我没 commit？分支搞错了？
    - 遇到问题无法在线上 debug，难道只能通过加日志再重新发布吗？
    - 线上遇到某个用户的数据处理有问题，但线上同样无法 debug，线下无法重现！
    - 是否有一个全局视角来查看系统的运行状况？
    - 有什么办法可以监控到JVM的实时运行状态？
    - 怎么快速定位应用的热点，生成火焰图？

- Arthas支持JDK 6+，支持Linux/Mac/Windows，采用命令行交互模式，同时提供丰富的 Tab 自动补全功能，进一步方便进行问题的定位和诊断。

[目录](#目录)
