---
layout: post
title: 项目过程中的一些异常
categories: java异常
description: 记录下自己解决的异常
keywords: Java
---
博文主要介绍了博主项目过程中碰到的异常问题，以及如何解决的，下次留个心


在做项目的过程中，遇到较多让人头疼的异常，但还是静下心来认真地花时间把它们解决了，没想到千辛万苦地解决以后，迎来竟这么大的满足感和成就感，这也许就是编程的魅力之一吧。
想着把这些问题记录下来，自己多回顾，以后再遇到相似的问题解决起来也更容易。

项目过程中，在使用BigDecimal来将两个数相加时，遇到空指针异常，花了很长时间来找原因，后来发现是其中相加的两个参数其中有一个引用为null，因此加了if null的判读，并将其初始化为0，这样一来，就避免了空指针，程序正常运行。
感觉很开心，又成功解决一处问题，收获很多

最后成功的测试结果：

![异常处理](https://github.com/AndyofJuly/andyofjuly.github.io/blob/master/images/newimage/ex-nullpoint.png)
![](/images/newimage/ex-nullpoint.png)
