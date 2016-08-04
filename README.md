# node学习

##简单介绍

Node.js 是一个让 JavaScript 运行在服务端的开发平台

###异步式 I/O 与事件驱动

Node.js 使用的是单线程模型，对于所有 I/O 都采用异步式的请求方式，避免了频繁的上下文切换

Node.js 在执行的过程中会维护一个事件队列，程序在执行时进入事件循环等待下一个事件到来，每个异步式 I/O 请求完成后会被推送到事件队列，等待程序进程进行处理。

###node命令行工具

运行无参数的node，将会启动一个javascript的交互式shell

连续连词ctrl+C即可退出node.js的REPL模式