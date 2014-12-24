---
layout: post
title: "golang常用库“
categories: 个人
tags: golang
excerpt: 个人收集的一些golang库

---
| 库 | 描述 |
| ------ | ------ |
|[debug](https://github.com/funny/debug)|使用`Print`打印出调试信息，并且同时输出调用堆栈|
|[unitest](https://github.com/funny/unitest)|这是一个单元测试工具库，用来降低Go语言项目单元测试的代码复杂度。<br>调用unitest.Pass可以减少很多不必要的判断语句和错误信息<br>进程监控：记录内存增长和GC情况（获取当前所有goroutine的堆栈跟踪信息用于排查死锁等情况。获取当前内存状态信息，包含内存分配情况和GC暂停时间等。 获取当前线程创建信息况，通常用来排查CGO的线程使用情况<br>[详情](https://github.com/funny/unitest/blob/master/README_CN.md)|
|[overall](https://github.com/funny/overall)|这个包可以帮你监控你的Go应用的总体运行情况。<br>GC综合情况M<br>监控执行时间<br>[详情](https://github.com/funny/overall/blob/master/README_CN.md)|
|[sync](https://github.com/funny/sync) |这个包用来在开发调试期，帮助排查程序中的死锁情况。（golang1.4出现问题无法取得goroutine id）|

---
[我labs](https://github.com/NicholeGit/notes/tree/master/golang/README.md)




