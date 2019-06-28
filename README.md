

# Android 高级面试

### ![面试](img/面试.png)写给Android的一封信

最近半年，常常有人问我 “Android就业市场究竟怎么样，我还能不能坚持下去 ?”

现在想想，移动互联网的发展不知不觉已经十多年了，Mobile First 也已经变成了 AI First。换句话说，我们已经不再是“风口上的猪”。移动开发的光环和溢价开始慢慢消失，并且正在向 AI、区块链等新的领域转移。移动开发的新鲜血液也已经变少，最明显的是国内应届生都纷纷涌向了 AI 方向。

​       可以说，国内移动互联网的红利期已经过去了，现在是增量下降、存量厮杀，从争夺用户到争夺时长。比较明显的是手机厂商纷纷互联网化，与传统互联网企业直接竞争。另外一方面，过去渠道的打法失灵，小程序、快应用等新兴渠道崛起，无论是手机厂商，还是各大 App 都把出海摆到了战略的位置。



各大培训市场也不再培训Android，**作为开发Android的我们该何去何从？**



​        其实如果你技术深度足够，大必不用为就业而忧愁。每个行业何尝不是这样，最开始的风口，到慢慢的成熟。Android初级在2019年的日子里风光不再， 靠会四大组件就能够获取到满意薪资的时代一去不复返。**经过一波一波的淘汰与洗牌，剩下的都是技术的金子。就像大浪褪去，裸泳的会慢慢上岸。**而真正坚持下来的一定会取得不错成绩。毕竟Android市场是如此之大。从Android高级的蓬勃的就业岗位需求来看，能坚信我们每一位Android开发者的梦想 。

 接下来我们针对Android高级展开的完整面试题 



## 预习专区

- [Android预习专题](./android/README.md)

  - [你知道什么是AOP吗？AOP与OOP有什么区别，谈谈AOP的原理是什么](android/aop.md)

    

## 2019Android年高级面试

 * [2019年Bat面试集合](#2019年Bat面试集合)
 * [架构相关面试](#架构相关面试)
 * [NDK相关面试](#NDK相关面试)
 * [算法相关面试](#算法相关面试)
 * [高级UI相关面试](#高级UI相关面试)
 * [性能优化相关面试](#性能优化相关面试)
 * [专业领域相关面试](#专业领域相关面试)
 * [其他](#其他)


### 2019年Bat面试集合

> 阿里巴巴面试集合

* [谈谈线程池原理](android/thread1.md)
* [垃圾回收机制是如何实现的](android/traked.md)
* [https原理你知道吗](android/https.md)
* [Hadler是如何实现线程通信的](study/framework/Android消息机制.md)
* [Glide对Bitmap的缓存与解码复用如何做到的](android/thread.md)
* [给你一个Demo 你如何快速定位ANR](android/anr.md)
* [说说你对Dalvik虚拟机的认识 ](android/dalvik.md)
* [接下来说说 Android 虚拟机Dalvik与ART区别在哪里？](android/artordalvik.md)
* [有用过插件化吗？谈谈插件化原理？](android/plugin.md)
* [进程保活如何做到，你们保活率有多高？](android/process.md)
* [详细说说Binder通信原理与机制](android/binder.md)
* [Handler的原理是什么?能深入分析下 Handler的实现机制吗？](./study/framework/Handler机制源码.md)
* [ Handler中有Loop死循环，为什么没有阻塞主线程，原理是什么](study/framework/Android消息机制.md)
* [ AMS在Android的作用是什么，Activtiy启动跟AMS有什么关系](android/ams.md)
* [ PMS之前了解过吗?你对PMS怎么看的，能聊聊PMS的详细实现流程吗](android/pms.md)

> 腾讯面试集合

- [热修复连环炮(热修复是什么  有接触过tinker吗，tinker原理是什么)](tencent/tinker.md)
- [增量升级为什么减少升级代价，增量升级原理](tencent/update.md)
- [数据库版本如何单独升级，并且将原有数据迁移过去](tencent/sqlite.md)
- [如何设计一个多用户，多角色的App架构](android/thread.md)
- [谈谈volatile关键字与synchronized关键字在内存的区别](android/volatile.md)
- [synchronize关键字在虚拟机执行原理是什么，能谈一谈什么是内存可见性，锁升级吗](android/synchronize.md)
- [ButterKnife为什么执行效率为什么比其他注入框架高？它的原理是什么](android/butterknife.md)
- [Linux自带多种进程通信方式，为什么Android都没采用二偏偏使用Binder通信](android/binder1.md)
- [谈一谈Binder的原理和实现一次拷贝的流程](android/binder2.md)
- [组件化如何实现，组件化与插件化的差别在哪里，该怎么选型](android/commpont.md)
- [说下组件之间的跳转和组件通信原理机制](android/commpontrounter.md)
- [类比于微信，如何对Apk进行极限压缩,谈下Android压缩8大步 ](android/AndResGuard.md)
- [如何彻底防止反编译，dex加密怎么做 ](android/dex.md)

> 字节跳动面试集合

- [之前有做过直播吗?你们是通过什么方式实现直播的?](android/live.md)

- [抖音-直播中 网速比较差的条件下，如何使画面保证流畅的效果](android/live-optimitor.md)

- [抖音-谈下音视频同步原理，音频和视频能绝对同步吗](android/play_ffmpeg.md)

- [抖音-硬编码与软编码区别，如何选取硬编与软编](android/mediacodec.md)

- [抖音-抖音中时间特效与美颜特效怎么做的](android/thread.md)

- [抖音-Include、Merge、ViewStub的作用和原理](android/thread.md)

- [抖音-如何在脸部区域增加特效，怎样才能使这个特效跟随脸部](android/thread.md)

- [抖音-Include、Merge、ViewStub的作用和原理](android/thread.md)

- [抖音-Opencv中定位人脸的五个点是如何做到的](android/thread.md)

- [今日头条-为什么RecyclerView加载首屏会慢一些](android/thread.md)

- [今日头条-View绘制机制，onMeasure  onLayout ,onDraw方法的调用机制谈一下](android/thread.md)

- [今日头条-为什么Android会出现卡顿](android/thread.md)

- [今日头条-ThreadLocal底层原理和Handler的关系](android/thread.md)

- [今日头条-Flutter为什么会做到一处写 处处运行 与RN的区别](android/thread.md)

- [今日头条-Flutter的图形引擎与Android的渲染引擎原理](android/thread.md)

- [今日头条-sync关键字和lock的区别?  他们对线程的控制原理简单说下](android/thread.md)

  







### 架构相关面试

[EventBus源码详解与架构分析，使用EventBus会造成什么弊端](android/thread.md)

[AOP面向切面编程原理](android/thread.md)

[说说饿了么Hermes跨进程架构原理](android/thread.md)

[Message链表原理与重用机制是怎么实现](android/thread.md)

[QQ是怎么做到皮肤换肤的，谈谈换肤原理](android/thread.md)

[阿里巴巴ARouter原理执行流程，对组件化开发有什么好处](android/thread.md)

[RePlugin插件化通过什么方式实现强兼容](android/thread.md)

[谈谈对Rxjava的底层认识，如何做到线程切换的](android/thread.md)

[APT实现手写Dagger注入式框架](android/thread.md)

[-----持续更新   未完待续-------](#)



### NDK相关面试

 [Java中有指针吗？说说 为什么C会需要指针](android/thread.md)

[MakeFile编译一个so库的流程](android/thread.md)

[CmakeList.txt中find_library语法是什么意思](android/thread.md)

[谈谈阿里云andfix热修复原理](android/thread.md)

[直播推流中，通过rtmp协议发送一个packet包的流程](android/thread.md)

[直播中为什么需要将摄像头的NV21数据通过x264编码 再发送](android/thread.md)

[怎么编译一个FFmpeg 并且集成到AndroidStudio中](android/thread.md)

[webrtc是如何实现点对点通信的](android/thread.md)

[谈下webrtc 内网穿透原理](android/thread.md)

[-----持续更新   未完待续-------](#)





### 算法相关面试

- [Hash值是如何生成](./basic/1-algo/2-hash.md)
- [谈谈HashMap的原理](./basic/1-algo/2-hash.md)
- [最小生成树算法](./basic/1-algo/3-mst.md)
- [最短路径算法](./basic/1-algo/4-path.md)
- [KMP算法](./basic/1-algo/5-kmp.md)
- [查找算法](./basic/1-algo/6-search.md)
- [排序算法](./basic/1-algo/7-sort.md)
- [跳跃表](./basic/1-algo/9-skip_list.md)
- [对称加密与非对称加密是如何实现的](./basic/1-algo/9-skip_list.md)
- [-----持续更新   未完待续-------](#)



### 高级UI相关面试

[你知道Bat公司如何对屏幕适配的](android/thread.md)

[谈谈对刘海屏开发与适配方案](android/thread.md)

[Android9.0Api适配举例有哪些不一样的地方](android/thread.md)

[讲讲你对UI绘制流程及其原理的](android/thread.md)

[谈谈你对事件传递机制的认识](android/thread.md)

[在自定义View中如何开启硬件加速](android/thread.md)

[淘宝如何做到展示亿级商品（强排版，强交互实现机制）](android/thread.md)

[-----持续更新   未完待续-------](#)



### 专业领域相关面试

> Opengl面试

[-----持续更新   未完待续-------](#)



> 智能家居串口面试

[-----持续更新   未完待续-------](#)



> 图形识别Opencv面试

[-----持续更新   未完待续-------](#)

[摘自GitHub干货集合](https://github.com/interviewandroid/AndroidInterView)

#### 后续持续更新中，添加QQ群：4112676, 备注github

##### 加微信号，获取Android 2019年面试视频。发送"面试 "即可领取   另附企业内推，架构设计资料，相关视频资料

[![image](img/img.jpg)