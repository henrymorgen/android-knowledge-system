# Android最强原创知识体系


为了方便大家的阅读以及自己的知识体系的建立，特意来写出这个引导文章。以前我是遇到什么写什么，想到什么写什么，从2016年开始我将围绕这个知识体系来写文章，从点到面来逐步建立并完善自己的知识体系。对于Android应用开发知识体系的建立，我这里貌似是最早的，后面有很多人开始模仿，也算是带了个好头。

我这个知识体系和其他的知识体系不同的是所有的分支文章都是我原创写出来的，所以文章的风格会比较统一，文章之间的过度和衔接也比较自然。

很多人都有一个误区，就是喜欢搞个思维导图，思维导图本身并没有问题，但是弄个思维导图，然后每个分支总结下，或者找几篇文章看看甚至看都不看就列在分支下面，然后看着思维导图有了满满的成就感，以为自己掌握了，其实只是知道而已，真正的掌握是去实现每个例子，去跟踪每段源码... 然后经过思考用自己的话写出来，未经自己思考的知识不是知识。而本体系就是告诉你，应该如何做，才会把知识变为你自己的。


---
#### **BATcoder技术视频(基于Android 11.0)**
[一个视频帮你突破系统底层学习瓶颈！](http://liuwangshu.cn/batcoder/android-framework.html) 
[是时候安装Ubuntu，开始研究系统源码了！](http://liuwangshu.cn/batcoder/aosp/1-install-ubuntu.html) 
[是时候下载Android11系统源码和内核源码了！](http://liuwangshu.cn/batcoder/aosp/2-download-aosp.html) 
[做了多年安卓还没编译过源码？一个视频带你玩转！](http://liuwangshu.cn/batcoder/aosp/3-compiling-aosp.html)  



## **1.Android框架层**
[Android系统架构与系统源码目录](http://liuwangshu.cn/framework/system-architecture.html)
#### **AOSP基础（基于Android 9.0）**
[Android AOSP基础（一）VirtualBox 安装 Ubuntu](http://liuwangshu.cn/framework/aosp/1-install-ubuntu.html)               
[Android AOSP基础（二）AOSP源码和内核源码下载](http://liuwangshu.cn/framework/aosp/2-download-aosp.html)                
[Android AOSP基础（三）Android系统源码的整编和单编](http://liuwangshu.cn/framework/aosp/3-compiling-aosp.html)              
[Android AOSP基础（四）Source Insight和Android Studio导入系统源码](http://liuwangshu.cn/framework/aosp/4-import-aosp.html)                                              
[Android AOSP基础（五）Android Studio调试系统源码的三种方式](http://liuwangshu.cn/framework/aosp/5-debug-aosp.html)  


#### **系统启动流程（基于Android 7.0）**
[Android系统启动流程（一）解析init进程启动过程](http://liuwangshu.cn/framework/booting/1-init.html)                  
[Android系统启动流程（二）解析Zygote进程启动过程](http://liuwangshu.cn/framework/booting/2-zygote.html)             
[Android系统启动流程（三）解析SyetemServer进程启动过程](http://liuwangshu.cn/framework/booting/3-syetemserver.html)     
[ Android系统启动流程（四）Launcher启动过程与系统启动流程](http://liuwangshu.cn/framework/booting/4-launcher.html)     


#### **应用程序进程启动过程（基于Android 7.0）**
[Android应用程序进程启动过程（前篇）](http://liuwangshu.cn/framework/applicationprocess/1.html)                      
[Android应用程序进程启动过程（后篇）](http://liuwangshu.cn/framework/applicationprocess/2.html)


#### **深入理解四大组件（基于Android 7.0/8.0）**
[Android深入四大组件（一）应用程序启动过程](http://blog.csdn.net/itachi85/article/details/69388942)                     
[Android深入四大组件（二）Service的启动过程](http://liuwangshu.cn/framework/component/2-service-start.html)             
[Android深入四大组件（三）Service的绑定过程](http://liuwangshu.cn/framework/component/3-service-bind.html)              
[Android深入四大组件（四）广播的注册、发送和接收过程](http://liuwangshu.cn/framework/component/4-broadcastreceiver.html)                                                                                                               
[Android深入四大组件（五）Content Provider的启动过程](http://liuwangshu.cn/framework/component/5-contentprovider-start.html)                               
[Android深入四大组件（六）Android8.0 根Activity启动过程（前篇）](http://liuwangshu.cn/framework/component/6-activity-start-1.html)                              
[Android深入四大组件（七）Android8.0 根Activity启动过程（后篇）](http://localhost:5000/framework/component/7-activity-start-2.html)                          
更多见《Android进阶解密》


#### **Binder原理（基于Android 9.0）**
[Android Binder原理（一）学习Binder前必须要了解的知识点](http://liuwangshu.cn/framework/binder/1-intro.html)             
[Android Binder原理（二）ServiceManager中的Binder机制](http://liuwangshu.cn/framework/binder/2-servicemanager-binder.html)                                                                                                                
[Android Binder原理（三）系统服务的注册过程](http://liuwangshu.cn/framework/binder/3-addservice.html)                       
[Android Binder原理（四）ServiceManager的启动过程](http://liuwangshu.cn/framework/binder/4-servicemanager-start.html)                                                                                                           
[Android Binder原理（五）系统服务的获取过程](http://liuwangshu.cn/framework/binder/5-getservice.html)                  
[Android Binder原理（六）Java Binder的初始化](http://liuwangshu.cn/framework/binder/6-java-binder-initialize.html)


#### **深入理解Context(基于Android 7.0)**

[Android深入理解Context（一）Context关联类和Application Context创建过程](http://liuwangshu.cn/framework/context/1-application-context.html)                                    
[Android深入理解Context（二）Activity和Service的Context创建过程](http://liuwangshu.cn/framework/context/2-activity-service.html)


#### **深入理解JNI(基于Android 7.1.2)**

[Android深入理解JNI（一）JNI原理与静态、动态注册](http://liuwangshu.cn/framework/jni/1-mediarecorder_register.html)          
[Android深入理解JNI（二）类型转换、方法签名和JNIEnv](http://liuwangshu.cn/framework/jni/2-signature-jnienv.html)

#### **解析AMS(基于Android 7.1.2)**
[Android解析ActivityManagerService（一）AMS启动流程和AMS家族](http://liuwangshu.cn/framework/ams/1-ams.html)              
[Android解析ActivityManagerService（二）ActivityTask和Activity栈管理](http://liuwangshu.cn/framework/ams/2-activitytask.html)
更多见《Android进阶解密》

#### **解析WindowManager(基于Android 7.1.2)**
[Android解析WindowManager（一）WindowManager体系](http://liuwangshu.cn/framework/wm/1-windowmanager.html)                 
[Android解析WindowManager（二）Window的属性](http://liuwangshu.cn/framework/wm/2-window-property.html)                
[Android解析WindowManager（三）Window的添加过程](http://liuwangshu.cn/framework/wm/3-add-window.html)

#### **解析WMS完结(基于Android 8.0)**
[Android解析WindowManagerService（一）WMS的诞生](http://liuwangshu.cn/framework/wms/1-wms-produce.html)                 
[Android解析WindowManagerService（二）WMS的重要成员和Window的添加过程](http://liuwangshu.cn/framework/wms/2-wms-member.html)
[Android解析WindowManagerService（三）Window的删除过程](http://liuwangshu.cn/framework/wms/3-wms-remove.html)
#### **包管理机制(基于Android 8.0)**
[Android包管理机制（一）PackageInstaller的初始化](http://liuwangshu.cn/framework/pms/1-packageinstaller-initialize.html)                                                                                                               
[Android包管理机制（二）PackageInstaller安装APK](http://liuwangshu.cn/framework/pms/2-packageinstaller-apk.html)         
[Android包管理机制（三）PMS处理APK的安装](http://liuwangshu.cn/framework/pms/3-pms-install.html)                       
[Android包管理机制（四）PMS的创建过程](http://liuwangshu.cn/framework/pms/4-pms-start.html)                          
[Android包管理机制（五）APK是如何被解析的](http://liuwangshu.cn/framework/pms/5-packageparser.html)

#### **输入系统(基于Android 8.1)**
[Android输入系统（一）输入事件传递流程和InputManagerService的诞生](http://liuwangshu.cn/framework/ims/1-ims-produce.html)                                                                                                                   
[Android输入系统（二）IMS的启动过程和输入事件的处理](http://liuwangshu.cn/framework/ims/2-inputevent.html)              
[Android输入系统（三）InputReader的加工类型和InputDispatcher的分发过程](http://liuwangshu.cn/framework/ims/3-inputdispatcher.html)                                                                                                                
[Android输入系统（四）输入事件是如何分发到目标窗口的？](http://liuwangshu.cn/framework/ims/4-inputtarget.html)

#### **Android多媒体框架(基于Android 2.3)**
[MediaPlayer框架概述（一）](http://blog.csdn.net/itachi85/article/details/7037427)                              
[MediaPlayer框架概述（二）](http://blog.csdn.net/itachi85/article/details/7040510)                                   
[Android mediaRecorder框架简述(一)](http://blog.csdn.net/itachi85/article/details/8278362)                            
[Android mediaRecorder框架简述(二)](http://blog.csdn.net/itachi85/article/details/8278742)                                      
[Android MediaPlayer+Stagefright框架（音频）图解](http://blog.csdn.net/itachi85/article/details/7215409)                     
[Stagefright框架解读（—）音视频Playback流程](http://blog.csdn.net/itachi85/article/details/7216639)

---
## **2.Android应用层**
#### **Gradle核心思想**
[Gradle核心思想（一）为什么现在要用Gradle？](http://liuwangshu.cn/application/gradle/1-study-gradle.html)                       
[Gradle核心思想（二）Gradle入门前奏](http://liuwangshu.cn/application/gradle/2-primer.html)                          
[Gradle核心思想（三）Groovy快速入门指南](http://liuwangshu.cn/application/gradle/3-groovy.html)                              
[Gradle核心思想（四）看似无用，实则重要的Gradle Wrapper](http://liuwangshu.cn/application/gradle/4-wrapper.html)             
[Gradle核心思想（五）通俗易懂的Gradle插件讲解](http://liuwangshu.cn/application/gradle/5-plugins.html)            
[Gradle核心思想（六）自定义Gradle插件的三种方式](http://liuwangshu.cn/application/gradle/6-custonplugin.html)

#### **Android Gradle插件**
[Android Gradle （一）Gradle的Android插件入门](http://liuwangshu.cn/application/gradle/1-study-gradle.html)             
[Android Gradle （二）签名配置和依赖管理](http://liuwangshu.cn/application/android-gradle/2-gradle-dependency.html)

#### **Android Jetpack架构组件**
[Android Jetpack架构组件（一）带你了解Android Jetpack](http://liuwangshu.cn/application/jetpack/1-study-jetpack.html)                                                       
[Android Jetpack架构组件（二）带你了解Lifecycle（使用篇）](http://liuwangshu.cn/application/jetpack/2-lifecycle-use.html)                                                                                                                
[Android Jetpack架构组件（三）带你了解Lifecycle（原理篇）](http://liuwangshu.cn/application/jetpack/3-lifecycle-theory.html)                                                                                                               
[Android Jetpack架构组件（四）带你了解LiveData(使用篇）](http://liuwangshu.cn/application/jetpack/4-livedata-use.html)                                                                                                                              
[Android Jetpack架构组件（五）带你了解LiveData(原理篇）](http://liuwangshu.cn/application/jetpack/5-livedata-theory.html)                                                                                                                  
[Android Jetpack架构组件（六）一文带你了解ViewModel的使用和原理](http://liuwangshu.cn/application/jetpack/6-viewmodel.html)

#### **解析ClassLoader** 
[Android解析ClassLoader（一）Java中的ClassLoader](http://liuwangshu.cn/application/classloader/1-java-classloader-.html)                                                                                                                      
[Android解析ClassLoader（二）Android中的ClassLoader](http://liuwangshu.cn/application/classloader/2-android-classloader.html)

#### **网络编程**
[ Android网络编程（一）HTTP协议原理](http://liuwangshu.cn/application/network/1-http.html)                                             
[Android网络编程（二）HttpClient与HttpURLConnection](http://liuwangshu.cn/application/network/2-httpclienthttp-urlconnection.html)                                                                                                        
[Android网络编程（三）Volley用法全解析](http://liuwangshu.cn/application/network/3-volley.html)                           
[Android网络编程（四）从源码解析volley](http://liuwangshu.cn/application/network/4-volley-sourcecode.html)                
[Android网络编程（五）OkHttp2.x用法全解析](http://liuwangshu.cn/application/network/5-okhttp2x.html)                   
[Android网络编程（六）OkHttp3用法全解析](http://liuwangshu.cn/application/network/6-okhttp3.html)                      
[ Android网络编程（七）源码解析OkHttp前篇[请求网络]](http://liuwangshu.cn/application/network/7-okhttp3-sourcecode.html)                                                                                                                         
[Android网络编程（八）源码解析OkHttp后篇[复用连接池]](http://liuwangshu.cn/application/network/8-okhttp3-sourcecode2.html)                                                                                                                                                                                                                                                                    
[Android网络编程（九）Retrofit2前篇[基本使用]](http://liuwangshu.cn/application/network/9-retrofit2.html)              
[Android网络编程（十）Retrofit2后篇[注解]](http://liuwangshu.cn/application/network/10-retrofit2-annotations.html)   
[ Android网络编程（十一）源码解析Retrofit](http://liuwangshu.cn/application/network/11-retrofit2-sourcecode.html)


#### **View体系**
[ Android View体系（一）视图坐标系](http://liuwangshu.cn/application/view/1-coordinate-system.html)                        
[Android View体系（二）实现View滑动的六种方法](http://liuwangshu.cn/application/view/2-sliding.html)                       
[Android View体系（三）属性动画](http://liuwangshu.cn/application/view/3-animation.html)                               
[ Android View体系（四）从源码解析Scroller](http://liuwangshu.cn/application/view/4-scroller-sourcecode.html)           
[Android View体系（五）从源码解析View的事件分发机制](http://liuwangshu.cn/application/view/5-dispatchingevents.html)     
[ Android View体系（六）从源码解析Activity的构成](http://liuwangshu.cn/application/view/6-activity-constitute.html)        
[Android View体系（七）从源码解析View的measure流程](http://liuwangshu.cn/application/view/7-measure-sourcecode.html)   
[ Android View体系（八）从源码解析View的layout和draw流程](http://liuwangshu.cn/application/view/8-layout-sourcecode.html)                                                                                                                  
[Android View体系（九）自定义View](http://liuwangshu.cn/application/view/9-custom-view.html)                                   
[ Android View体系（十）自定义组合控件](http://liuwangshu.cn/application/view/10-custom-group.html)                          
[Android View体系（十一）自定义ViewGroup](http://liuwangshu.cn/application/view/11-custom-viewgroup.html)                

#### **IPC机制**
[Android IPC机制（一）开启多进程](http://liuwangshu.cn/application/ipc/1-process-start.html)                         
[Android IPC机制（二）用Messenger进行进程间通信](http://liuwangshu.cn/application/ipc/2-messenger.html)                     
[ Android IPC机制（三）在Android Studio中使用AIDL实现跨进程方法调用](http://liuwangshu.cn/application/ipc/3-aidl.html)                                    
[Android IPC机制（四）用ContentProvider进行进程间通信](http://liuwangshu.cn/application/ipc/4-contentprovider.html)         
[Android IPC机制（五）用Socket实现跨进程聊天程序](http://liuwangshu.cn/application/ipc/5-socket.html)

#### **Design Support Library**

[ Android Design Support Library（一）用TabLayout实现类似网易选项卡动态滑动效果](http://liuwangshu.cn/application/md/1-tablayout.html)                                                                                                   
[Android Design Support Library（二）用NavigationView实现抽屉菜单界面](http://liuwangshu.cn/application/md/2-navigationview.html)                                                                                                           
[Android Design Support Library（三）用CoordinatorLayout实现Toolbar隐藏和折叠](http://liuwangshu.cn/application/md/3-coordinatorlayout.html)                                                                                                     
 更多内容见《Android进阶之光》

#### **Android新特性**
[ Android5.x RecyclerView 应用解析](http://liuwangshu.cn/application/feature/5x-recyclerview.html)                    
[Android5.x CardView 应用解析](http://liuwangshu.cn/application/feature/5x-cardview.html)
[ Android5.x Notification应用解析](http://liuwangshu.cn/application/feature/5x-notification.html)                     
[Android5.x Toolbar和Palette应用解析](http://liuwangshu.cn/application/feature/5x-toolbar.html)

 更多内容见《Android进阶之光》
 
#### **Android性能优化**
[Android绘制优化（一）绘制性能分析](http://liuwangshu.cn/application/performance/draw-1-performance.html)            
[Android绘制优化（二）布局优化](http://liuwangshu.cn/application/performance/draw-2-layout.html)

[Android内存优化（一）DVM和ART原理初探](http://liuwangshu.cn/application/performance/ram-1-dvm-art.html)              
[Android内存优化（二）DVM和ART的GC日志分析](http://liuwangshu.cn/application/performance/ram-2-gc.html)                
[Android内存优化（三）避免可控的内存泄漏](http://liuwangshu.cn/application/performance/ram-3-memory-leak.html)             
[Android内存优化（四）解析Memory Monitor、Allocation Tracker和Heap Dump](http://liuwangshu.cn/application/performance/ram-4-memory-tools.html)                                          
[Android内存优化（五）详解内存分析工具MAT](http://liuwangshu.cn/application/performance/ram-5-mat.html)                
[Android内存优化（六）LeakCanary使用详解](http://liuwangshu.cn/application/performance/ram-6-leakcanary.html)              

#### **Android架构**
[ Android架构（一）MVP全解析](http://liuwangshu.cn/tags/Android%E6%9E%B6%E6%9E%84/)

 更多内容见《Android进阶之光》
 

####  **Android响应式编程**
[ Android响应式编程（一）RxJava前篇[入门基础]](http://liuwangshu.cn/application/reactive/rxjava-1-introduction.html)

 更多内容见《Android进阶之光》
 

#### **Android事件总线**
[ Android事件总线（一）EventBus3.0用法全解析](http://liuwangshu.cn/application/eventbus/1-eventbus.html)                
[ Android事件总线（二）EventBus3.0源码解析](http://liuwangshu.cn/application/eventbus/2-eventbus-sourcecode.html)            
[Android事件总线（三）otto用法全解析](http://liuwangshu.cn/application/eventbus/3-otto-sourcecode.html)                  
[Android事件总线（四）源码解析otto](http://liuwangshu.cn/application/eventbus/4-otto-sourcecode.html)


#### **热修复插件化原理**
 [ Android热修复原理（一）热修复框架对比和代码修复](http://liuwangshu.cn/application/hotfix/1-code-repair.html)            
  [ Android插件化原理（一）Activity插件化](http://liuwangshu.cn/application/plug-in/1.activity.html)                        
  更多见《Android进阶解密》
#### **Android多线程**
[Android多线程（一）线程池](http://blog.csdn.net/itachi85/article/details/44874511)                                  
[ Android多线程（二）AsyncTask源码分析](http://blog.csdn.net/itachi85/article/details/45041923)                     
[ Android多线程（三）AsyncTask源码分析（android7.0）](http://blog.csdn.net/itachi85/article/details/52858426)


#### **Android 界面编程**
[ Android 实现广告Banner循环轮播](http://blog.csdn.net/itachi85/article/details/50072619)                                
[ Android选项卡动态滑动效果](http://blog.csdn.net/itachi85/article/details/50358102)                                   
[ ActionBar-PullToRefresh的使用](http://blog.csdn.net/itachi85/article/details/41246039)


#### **Android面试总结加强版**
[Android面试题总结加强版（一）](http://blog.csdn.net/itachi85/article/details/7426451)                                   
[Android面试题总结加强版（二）](http://blog.csdn.net/itachi85/article/details/7426457)                               
[Android面试题总结加强版（三）](http://blog.csdn.net/itachi85/article/details/7426474)                               
[Android面试题总结加强版（四）](http://blog.csdn.net/itachi85/article/details/8037989)            

---
## **3.Flutter**
#### **Flutter基础**
[Flutter基础（一）移动开发的跨平台技术演进](http://liuwangshu.cn/flutter/primer/1-cross-platform-evolution.html)            
[Flutter基础（二）Flutter开发环境搭建和Hello World](http://liuwangshu.cn/flutter/primer/2-start.html)                
[Flutter基础（三）Dart快速入门](http://liuwangshu.cn/flutter/primer/3-dart.html)                                     
[Flutter基础（四）开发Flutter应用前需要掌握的Basic Widget](http://liuwangshu.cn/flutter/primer/4-basics-widget.html)        
[Flutter基础（五）Material组件之MaterialApp、Scaffold、AppBar](http://liuwangshu.cn/flutter/primer/5-material-components.html)                                              
[Flutter基础（六）Material组件之BottomNavigationBar、TabBar、Drawer](http://liuwangshu.cn/flutter/primer/6-material-components-2.html)                                                                                                       
[Flutter基础（七）Scrolling Widget之ListView、GridView、PageView](http://liuwangshu.cn/flutter/primer/7-scrolling-widget.html)                                                                                                           
[Flutter基础（八）手势相关Widget：GestureDetector和Dismissible](http://liuwangshu.cn/flutter/primer/8-gesture-widget.html)                                                                                                            
[Flutter基础（九）资源和图片](http://liuwangshu.cn/flutter/primer/9-assets-images.html)                                               
[Flutter基础（十）布局Widget快速入门](http://liuwangshu.cn/flutter/primer/10-layout-widget.html)                     
[Flutter基础（十一）网络请求（Dio）与JSON数据解析](http://liuwangshu.cn/flutter/primer/11-dio-json.html)                     
[Flutter基础（十二）路由（页面跳转）与数据传递](http://liuwangshu.cn/flutter/primer/12-route.html)                       
[Flutter基础（十三）Flutter与Android的相互通信](http://liuwangshu.cn/flutter/primer/13-platform-channel.html)


---
## **4.Java**
#### **Java并发编程**
[Java并发编程（一）线程定义、状态和属性](http://liuwangshu.cn/java/concurrent/1-thread.html)                          
[ Java并发编程（二）同步](http://liuwangshu.cn/java/concurrent/2-synchronous.html)                                       
[Java并发编程（三）volatile域](http://liuwangshu.cn/java/concurrent/3-volatile.html)                                   
[Java并发编程（四）Java内存模型](http://liuwangshu.cn/java/concurrent/4-jmm.html)                                       
[ Java并发编程（五）ConcurrentHashMap的实现原理和源码分析](http://liuwangshu.cn/java/concurrent/5-concurrenthashmap.html)                                                                                                                      
[Java并发编程（六）阻塞队列](http://liuwangshu.cn/java/concurrent/6-blockingqueue.html)                                         
[Java并发编程（七）ConcurrentLinkedQueue的实现原理和源码分析](http://liuwangshu.cn/java/concurrent/7-concurrentlinkedqueue.html)

#### **Java虚拟机**
[Java虚拟机（一）结构原理与运行时数据区域](http://liuwangshu.cn/java/jvm/1-runtime-data-area.html)                      
[Java虚拟机（二）对象的创建与OOP-Klass模型](http://liuwangshu.cn/java/jvm/2-oop-kclass.html)                           
[Java虚拟机（三）垃圾标记算法与Java对象的生命周期](http://liuwangshu.cn/java/jvm/3-garbage-mark.html)                     
[Java虚拟机（四）垃圾收集算法](http://liuwangshu.cn/java/jvm/4-garbage-collection.html)

---
## **5.设计模式**
[ 设计模式（一）设计六大原则](http://liuwangshu.cn/designpatterns/1-principle.html)                                 
**创建型模式**                                                                                                           
[设计模式（二）单例模式的七种写法](http://liuwangshu.cn/designpatterns/2-singleton.html)                                                              
[设计模式（三）建造者模式](http://liuwangshu.cn/designpatterns/3-builder.html)                                                
[设计模式（四）简单工厂模式](http://liuwangshu.cn/designpatterns/4-simplefactory.html)                                 
[设计模式（十）工厂方法模式](http://liuwangshu.cn/designpatterns/10-factorymethod.html)                          
[设计模式（十三）抽象工厂模式](http://liuwangshu.cn/designpatterns/13-abstractfactory.html)                                       
[设计模式（十六）原型模式](http://liuwangshu.cn/designpatterns/16-prototype.html)

**结构型模式 (从程序的结构上解决模块之间的耦合问题)**                                                                
[设计模式（六）代理模式](http://liuwangshu.cn/designpatterns/6-proxy.html)                                              
[设计模式（七）装饰模式](http://liuwangshu.cn/designpatterns/7-decorative.html)                                        
[设计模式（八）外观模式](http://liuwangshu.cn/designpatterns/8-facade.html)                                                
[设计模式（十二）享元模式](http://liuwangshu.cn/designpatterns/12-flyweight.html)

**行为型模式 (处理类或对象如何交互及如何分配职责)**                                                                  
[设计模式（五）观察者模式](http://liuwangshu.cn/designpatterns/5-observer.html)                                            
[ 设计模式（九）模版方法模式](http://liuwangshu.cn/designpatterns/9-templatemethod%20.html)                               
[设计模式（十一）策略模式](http://liuwangshu.cn/designpatterns/11-strategy.html)                                       
[设计模式（十四）中介者模式](http://liuwangshu.cn/designpatterns/14-mediator.html)                                         
[设计模式（十五）状态模式](http://liuwangshu.cn/designpatterns/15-state.html)


---
## **6.React Native**
**React Native探索**                                                                                                    
[React Native探索（一）环境搭建与Hello World](http://liuwangshu.cn/rn/primer/1-helloworld.html)                            
[React Native探索（二）Atom+Nuclide安装、配置与调试](http://liuwangshu.cn/rn/primer/2-atom-nuclide.html)                 
[React Native探索（三）组件的Props(属性)和State(状态)](http://liuwangshu.cn/rn/primer/3-props-state.html)                
[React Native探索（四）Flexbox布局详解](http://liuwangshu.cn/rn/primer/4-flexbox.html)                                  
[React Native探索（五）使用fetch进行网络请求](http://liuwangshu.cn/rn/primer/5-fetch.html)                             
**React Native组件**                                                                                                      
[React Native组件（一）组件的生命周期](http://liuwangshu.cn/rn/component/1-lifecycle.html)                        
[React Native组件（二）View组件解析](http://liuwangshu.cn/rn/component/2-view.html)                                       
[React Native组件（三）Text组件解析](http://liuwangshu.cn/rn/component/3-text.html)


---
## **7.算法**
[算法（一）时间复杂度](http://blog.csdn.net/itachi85/article/details/54882603)                                          
[算法（二）初等排序前篇[插入和希尔排序]](http://blog.csdn.net/itachi85/article/details/55657826)                        
[算法（三）初等排序后篇[选择和冒泡排序]](http://blog.csdn.net/itachi85/article/details/59488857)

---
## **8.Swift**
[Swift快速入门（一）第一个Swift程序](http://blog.csdn.net/itachi85/article/details/50531727)                           
[ Swift快速入门（二）基本数据类型](http://blog.csdn.net/itachi85/article/details/50596987)                           
[ Swift快速入门（三）运算符](http://blog.csdn.net/itachi85/article/details/50638125)                                      
[Swift快速入门（四）流程控制](http://blog.csdn.net/itachi85/article/details/50658955)                                      
[Swift快速入门（五）集合](http://blog.csdn.net/itachi85/article/details/50809810)

---

这里不仅分享大前端、Android、Java等技术，还有程序员成长类文章。

![](https://s2.ax1x.com/2019/10/24/KtXbJs.jpg)
