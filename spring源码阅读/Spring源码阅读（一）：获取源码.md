# Spring源码阅读（一）：获取源码

Spring是2003年开始兴起的一个框架，发展到今天已是非常的强大。对于工作2、3年的人在面试的时候，可能都会被问到是否看过开源框架的源码，以及谈谈你看过源码之后的心得或者见解之类的问题。今天这篇文章主要写给初学者，解决大家阅读源码的一些疑问和困难。

## 一、配置环境

因为Spring的源码采用的是gradle工具构建，所以需要先下载gradle工具。gradle是一个类似Maven的构建工具。如果对Maven或者Gradle都不熟悉，建议可以先了解一下gradle或者Maven。

### 1.1、Gradle的安装和配置

Gradle安装之前需要安装Jdk环境。我相信大家既然都学到Spring了，那肯定已经配置了JDK的环境。所以，在此至讲解Gradle的配置方式。

a、下载gradle：https://gradle.org/releases/

b、下载完毕之后，解压缩就行。

### 1.2、Gradle整合IDEA。

源码放到idea中查看会比较方便，所以接下来需要配置gradle整合idea。

1、打开idea的“settings”窗口，查找gradle配置，如下图：

![018050414055](https://github.com/yangjingwen2/javen666.com/blob/master/spring%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB/images/20180504140557.png?raw=true)

2、如上图红色箭头处，配置gradle的路径。之后点击“OK”按钮就行。



## 二、下载源码，并导入IDEA

### 2.1、下载源码

Spring源码在Github上。下载地址：https://github.com/spring-projects/spring-framework，如下图：

![018050414240](https://github.com/yangjingwen2/javen666.com/blob/master/spring%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB/images/20180504142402.png?raw=true)

点击绿色按钮，然后再点击“Download ZIP”按钮，等着下载完毕就行。

### 2.2、源码导入IDEA

源码下载好之后，就可以导入IDEA中了。步骤如下：

1、点击idea中的open project选项。

2、选择刚刚下载的spring源码目录（下载下来是zip压缩包，需要解压缩）。

3、等着初始化完毕。

导入完毕之后如图所示：

![018050414315](https://github.com/yangjingwen2/javen666.com/blob/master/spring%E6%BA%90%E7%A0%81%E9%98%85%E8%AF%BB/images/20180504143151.png?raw=true)



之后，就可以阅读源码了。



## 三、更简单的源码获取方式

如果项目使用的Maven构建，想查看Spring的源码，直接再spring的方法上点击“ctrl+鼠标左键”就可以进入源码界面。开发时，我阅读源码的方式，更多是采用这种方式。因为这种方式简单直接。



## 四、其他

阅读源码，不是为了读源码而去读源码。因为源码读起来是比较枯燥难受的。我们应该带着问题去读源码，从而通过源码找到具体的答案。这样读源码会更有意思、也会更明白源码的表达。

