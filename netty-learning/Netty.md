
# Netty

**本文章摘抄自 《Netty in Action》(Netty实战)，再根据本人实际学习体验总结而成，
所以本文内容可能不那么全面，但是我尽量挑选Netty中我认为比较重要的部分做讲解。**

学习Netty，相信大部分同学都会选择 《Netty in Action》 ， 这里我推荐它的一个Gitbook精髓版本的，
此版本的作者对《Netty in Action》做出了更为精简的概述，所以各位同学可酌情挑选阅读。


- [Netty in Action(精髓)](https://waylau.com/essential-netty-in-action/index.html)


````text
如有错误之处，敬请指教。
````

## Netty是什么?

Netty是一个利用Java的高级网络能力，隐藏其(Java API)背后的复杂性而提供一个易于使用的 NIO 客户端/服务端框架。
Netty提供了高性能和可扩展性，让你自由地专注于你真正感兴趣的东西。 Netty简化了网络程序的开发过程，使用它
我们可以快速简单地开发网络应用程序，比如客户端和服务端的通信协议，TCP和UDP的Socket开发。

在学习Netty之前，我们需要对 IO模型(网络IO模型)有一个大概的认知，可以参考我编写的：
[IO](https://guang19.github.io/framework-learning/gitbook_doc/jdk-jvm-juc/IO.html) 。