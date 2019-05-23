# Android-Senior
Java基础知识，Android知识，网络（Retrofit,RxJava），算法，设计模式，常用第三方框架

## Java基础
### Java相关 

[java堆、栈、堆栈的区别](https://www.cnblogs.com/iliuyuet/p/5603618.html)

[强引用、弱引用、软引用、虚引用](https://www.cnblogs.com/dolphin0520/p/3784171.html)

[jvm相关](https://www.cnblogs.com/dingyingsi/p/3760447.html)

[Java内存结构及分区（堆、栈）](https://blog.csdn.net/wanghuiwei888/article/details/78883326)

[Java对象的创建、存储及访问](https://www.cnblogs.com/z-sm/p/7145180.html?utm_source=itdadao&utm_medium=referral)

[Java判断对象是否存活及垃圾回收算法（GC）](https://blog.csdn.net/clover_lily/article/details/80152300)

[Jvm中的常见的垃圾回收器](https://www.cnblogs.com/1024Community/p/honery.html#%E5%9B%9B%E5%B8%B8%E8%A7%81%E7%9A%84%E5%9E%83%E5%9C%BE%E6%94%B6%E9%9B%86%E5%99%A8)

[Java类加载过程](https://www.cnblogs.com/xiaoxian1369/p/5498817.html)

[Java类加载器（双亲委派模型）](https://www.cnblogs.com/doit8791/p/5820037.html)

[Java泛型基础](https://www.toutiao.com/a6685474413103546884/?tt_from=weixin&utm_campaign=client_share&wxshare_count=1&timestamp=1556597473&app=news_article&utm_source=weixin&utm_medium=toutiao_ios&req_id=201904301211120100160441946828BDD&group_id=6685474413103546884)

### 集合相关

[ArrayList分析](https://www.cnblogs.com/xujian2014/p/4625346.html)

[LinkedList分析](https://www.cnblogs.com/leskang/p/6029780.html)

HashMap分析

HashTable分析

LinkedHashMap分析

HashSet分析

LinkedHashSet分析

[ArrayMap、SparseArray、与HashMap的对比](https://www.cnblogs.com/zly1022/p/7743466.html)

ConcurrentHashMap分析

### 并发相关

Java内存模型

volatile原理

Synchronized的原理

AQS原理

Condition原理

ReentrantLock 原理

公平锁与非公平锁

ReentrantReadWriteLock原理

### 线程相关

线程和进程的区别

线程的启动和终止

线程间通信

等待/通知机制

### 线程池相关

使用线程池的原因

线程池内部原理

线程池中的几种重要的参数及流程说明

线程池中几种常见的工作队列

几种常见的线程池及使用场景。

### IO相关

IO相关面试问题-Socket

IO相关面试问题-BIO／NIO

### 注解
[RetentionPolicy]{https://www.jianshu.com/p/208c2ee5f18b}

## 算法相关
常见的八大排序方式

时间复杂度的计算

链表相关算法，链表翻转，链表合并等

二叉树相关算法前序、中序、后序遍历（递归，迭代）

​红黑树与BL树

## Android知识

### 屏幕适配
[今日头条适配方式](https://www.jianshu.com/p/1eeb0d8d1c86)

[宽高限定符适配方式]

smallestWidth适配
   
### ART
[ART虚拟机](https://www.cnblogs.com/manuosex/p/3634375.html)

### Activity相关

典型状况下的生命周期

异常情况下的生命周期

异常情况下的数据保存

各种情况下跳转到某个Activity时目标Activity及当前Activity的生命周期

Activity的启动模式及应用场景

进程和应用生命周期

### Service相关

Service的定义及作用

Service两种启动方式 startService、 bindService 区别及生命周期

Service绑定服务的三种实现方式，扩展Binder类、使用Messenger、使用AIDL

关于启动服务与绑定服务间的转换问题 先绑定服务后启动服务、先启动服务后绑定服务

服务Service与线程Thread的区别

Android 5.0以上的隐式启动问题及其解决方案

如何保证服务不被杀死

IntentService的使用及原理

### BroadcastReceiver相关

BroadcastReceiver定义及作用、应用场景

BroadcastReceiver的注册方式，静态方式、动态方式

BroadcastReceiver注册与取消的时机

BroadcastReceiver的不同类型，普通广播，系统广播、有序广播、粘性广播、应用类广播

### Fragment相关

Fragment生命周期

Fragment的懒加载

Fragment之间的通信

FragmentPagerAdapter与FragmentStatePagerAdapter的区别

为什么不建议直接通过使用new Fragment的方式传入数据

### 序列化相关

序列化与反序列化的定义及区别

Serializable中serialVersionUID及transient关键字的作用

序列化：Parcelable和Serializable差异

### IPC相关

在Android中什么样的情况下会使用多进程模式，如何开启多进程

Android为什么采用Binder做为IPC机制

IPC常用方式 使用Bundle、使用文件共享、使用Messenger、使用AIDL、使用ContentProvider、使用Socket

AIDL的语义

AIDL如何创建

AIDL生成Java文件详细分析

View事件机制相关

View的坐标体系

View滑动的几种方式，使用ScrollTo/ScrollBy、使用动画、改变布局参数

弹性滑动的原理及实现

View的事件分发机制，点击事件的传递规则，事件分发的源码解读

处理滑动冲突的场景及解决方法

### View绘制相关

DecorView、Window、ViewRootImpl等概念

MeasureSpec概念

View的工作流程，measure过程、layout过程、draw过程

自定义View需要注意的事项

Activity、Window、View三者之间的关系

### View动画相关

常用动画View动画（补间动画）、属性动画与帧动画

补间动画与属性动画区别

差值器和估值器理解

属性动画的工作原理

### Handler相关

Handler机制之ThreadLocal

Handler机制之Looper、Handler、消息队列如何理解

Handler机制之Message的发送与取出

Handler机制之Message及Message的回收机制

Handler机制之循环消息队列的退出

Handler机制之内存泄漏

Handler机制之IdleHandle的理解及使用

### AsyncTask相关

AsyncTask的使用和注意事项

AsyncTask几个重要的方法 doInBackgound、onProgressUpdate、onPostExecute等

AsyncTask的工作原理及源码理解

Bitmap压缩机回收相关

Bitmap所占内存

常用压缩图片方式

LruCache原理

DiskLruCache原理

LinkedHashMap原理

ListView与RecyclerView相关

ListView的原理和复用机制

ListView和RecyclerView的区别

### 数据存储相关

常用数据库框架GreenDao,官方Room

数据库数据迁移问题

GreenDao中一对一，一对多，多对多关系

SharedPreferences使用及源码，commit与apply()方法的区别

### Android 高版本差异

广播在7.0、8.0、9.0下的适配 
Android 6.0 权限下的适配 
Android 7.0应用共享文件（FileProvider) 
Android 7.0 共享文件的使用方式
[Android9.0新特性](https://blog.csdn.net/MYBOYER/article/details/87075761)
###蓝牙
[Blutooth](https://www.cnblogs.com/wenjiang/p/3200138.html)

### Android打包相关
安卓签名的理解

Gradle多渠道打包


   
   
## Android进阶
 ### 性能优化:

布局优化、绘制优化、线程优化等

ANR异常:主线程执行了耗时操作，如BroadcastReceiver(前台广播10s,后台广播为60s)、Service(前台20s,后台200s)没有处理完相关任务等

OOM异常：内存溢出的原因

内存泄漏：内存泄露的几种场景，如单例模式引出的泄露、静态变量导致的泄露、属性动画导致的内存泄露等

### Android架构相关

[腾讯，阿里，百度Android高级岗；全方位性能调优技术体系详解](https://juejin.im/post/5cc5a356518825250762c6ce)

MVC架构设计模式面试问题讲解

MVP架构设计模式面试问题讲解

MVVM架构设计模式面试问题讲解

###IPC
[Binder](https://www.cnblogs.com/xinmengwuheng/p/7070167.html)

## 第三方开源框架
OkHttp相关

OkHttp的优点

OkHttp执行请求的整个流程

OkHttp中的拦截器

OkHttp中的同步请求与异步请求的理解及其源码

OkHttp中涉及到的设计模式

OkHttp底层网络请求实现，socket还是URLConnection

Retrofit相关

Retrofit执行请求的整个流程

Retrofit中ConverterFactory、CallAdapterFactory的理解

Retrofit中CallAdapter的适配器模式

RxJava相关

RxJava常用创建操作符 create、from、just、interval、range等

RxJava常用组合、合并操作符 combineLatest、join、merge、zip等

RxJava错误处理操作符 onErrorReturn、onErrorResumeNext、onExceptionResumeNext等

RxJava过滤操作符 filter、ofType、sample、take等

Rxjava背压相关理解

RxJava实际开发中的使用：网络请求轮询、网络请求嵌套回调、从磁盘 / 内存缓存中 获取缓存数据等

Glide相关

Glide的执行流程

Glide的缓存机制

Glide图片转换

Glide带进度的图片加载功能

Glide内存、磁盘缓存，优先级使用

ButterKnife相关

Java注解相关Annotation

Java注解相关之APT工具

ButterKnife注解框架原理

EventBus相关

EventBus原理，及索引类的使用

[GreenDAO](https://www.cnblogs.com/whoislcj/p/5651396.html)

## 网络相关

计算机网络三种体系架构，OSI体系架构（7层）、TCP/IP体系架构(4层)，五层体系架构

TCP的连接管理（三报文握手，四报文握手）

TCP与UDP的理解与区别

Http（HyberText Transfer Protocol）基本概念及报文结构

Http常见错误码

Http1.0与Http1.1与Http2.0的区别

Http中get请求与post请求的区别

Http中cookie与session的区别

Http与Https的区别

Https加密算法相关面试问题，签名证书，公钥私钥、数字摘要的理解

## 设计模式相关

单例模式

Builder模式

装饰模式

策略模式

模板方法

观察者模式

工厂方法模式

状态模式

适配器模式

外观模式
