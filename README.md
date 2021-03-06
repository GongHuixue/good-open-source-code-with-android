# good-open-source-code-with-android

## 架构篇      
  名称                                                                 |               描述  
  -|                                                                  -|  
  [Android-ZBLibrary](https://github.com/TommyLemon/Android-ZBLibrary) | Android MVP快速开发框架，做国内 「Demo最全面」「注释最详细」「使用最简单」「代码最严谨」的Android开源UI框架。  
  [android-architecture](https://github.com/googlesamples/android-architecture)|来自google官方的关于MVP,MVC,MVVM,的sample demo
  [AndroidArchitectureCollection](https://github.com/CameloeAnthony/AndroidArchitectureCollection)|安卓架构文章合集（a collection of android Architecture）,看过的，介绍android架构最全的文章集合
  [Android](https://github.com/open-android/Android)|一个讲解koltin、android知识的集合，包含源码和视频.
  * 1 Android MVP+Retrofit+RxJava实践小结(http://wuxiaolong.me/2016/06/12/mvpRetrofitRxjava/)
    
## 网络篇
  名称                                                                 |               描述  
  -|                                                                  -|  
  [Volley](https://android.googlesource.com/platform/frameworks/volley)|Google 提供的网络通信库，使得网络请求更简单、更快速;适合轻量级网络交互，网络请求频繁，传输数据量小的场景.只能异步，不能同步。
  [okhttp](https://github.com/square/okhttp)|square 开源的 http 工具类，支持同步、异步请求；
  [retrofit](https://github.com/square/retrofit)|RESTFUL API 设计，通过注解配置请求，包括请求方法、请求参数、请求头、返回值等，提供Rxjava支持
  
  主流网络请求开源库的对比（Android-Async-Http、Volley、OkHttp、Retrofit）(https://www.jianshu.com/p/050c6db5af5a)   
  ![](https://upload-images.jianshu.io/upload_images/944365-f48072d21b613aaf.png)   
  >Volley
  * 1 来自郭霖大神的Volley教程(https://blog.csdn.net/RoseChan/article/details/51108105)
  >OkHttp
  * 1 OKHttp源码解析(http://www.jcodecraeer.com/a/anzhuokaifa/androidkaifa/2015/0326/2643.html)
  >Retrofit
  * 1 Retrofit2 完全解析 探索与okhttp之间的关系(https://blog.csdn.net/lmj623565791/article/details/51304204)
  * 2 Retrofit2完全教程(https://www.jianshu.com/p/308f3c54abdd)
  * 3 这是一份很详细的 Retrofit 2.0 使用教程(https://blog.csdn.net/carson_ho/article/details/73732076)
## 图片篇
  名称                                                                 |               描述  
  -|                                                                  -|  
  [PhotoView](https://github.com/chrisbanes/PhotoView)|Implementation of ImageView for Android that supports zooming, by various touch gestures.
  [Android-Universal-Image-Loader](https://github.com/nostra13/Android-Universal-Image-Loader)|图片缓存，目前使用最广泛的图片缓存，支持主流图片缓存的绝大多数特性。
  [Glide](https://github.com/bumptech/glide)|Glide 是一个 android 平台上的快速和高效的开源的多媒体资源管理库,提供 多媒体文件的压缩,内存和磁盘缓存, 资源池的接口。它可以最大性能地在 Android 设备上读取、解码、显示图片和视频。Glide 可以将远程的图片、视频、动画图片等缓存在设备本地便于提高用户浏览图片的流畅体验
  [fresco](https://github.com/facebook/fresco)|一款强大的图片缓存工具，由 Facebook 开发
  
Android 图片加载库，包括，glide，Picasso，Univisial-Image-loader的比较及区别。(https://www.jianshu.com/p/97994c9693f9)      
 >glide 讲解
 * 1 郭霖 glide源码解析1～8(https://blog.csdn.net/column/details/15318.html)
 * 2 深入解析glide源码【含流程图】(https://blog.csdn.net/u012124438/article/details/73612492)
 >Picasso 讲解
 * 1 Picasso 基本使用和源码完全解析(https://www.linuxprobe.com/picasso-basic-use.html)
 * 2 图片加载框架Picasso － 源码分析(https://www.jianshu.com/p/332bde48ccf2)
 >glide 与 Picasso的区别
 * 1 glide 可以加载视频，gif图片，Picasso不行。
 * 2 Picasso消耗的内存比glide 大。
 * 3 Picasso中context是全局的，而Glide是当前的。
  
## 多媒体  
  名称                                                                 |               描述  
  -|                                                                  -|  
  [MediaPlayer](https://github.com/QiMengChao/MediaPlayer)|仿QQ音乐播放器界面,实现简单本地的音频、视频播放.以及自己写的一款歌词控件
  [MusicPlayer](https://github.com/caohaoping/MusicPlayer)|MusicPlayer, 无广告，轻量级本地音乐播放器：自定义控件，左侧歌曲列表，中间是简洁的播放控件，在线匹配歌词，歌词自动转码播放。可上一首、下一首、单曲循环、顺序播放、随机播放，通知栏可控制播放状态。
  
## UI
  名称                                                                 |               描述  
  -|                                                                  -|  
  [awesome-android-ui](https://github.com/wasabeef/awesome-android-ui)|A curated list of awesome Android UI/UX libraries[介绍各种UI控件的demo]
  [开源库分类](https://blog.csdn.net/dpl12/article/details/78252974)|包括个性化控件，如listview，recycleriew,actionbar；图片缓存，网络处理，时间总线，版本兼容，安全，
  
* 1 Fragment     

  名称                                                                 |               描述  
  -|                                                                  -|  
  [Fragmentation](https://github.com/YoKeyword/Fragmentation)          |A powerful library that manage Fragment for Android!
  [ViewPagerIndicator](https://github.com/GongHuixue/ViewPagerIndicator)|Paging indicator widgets compatible with the ViewPager from the Android Support Library and ActionBarSherlock.
* 2 图表  

  名称                                                                 |               描述  
  -|                                                                  -|  
  [smartTable](https://github.com/huangyanbin/smartTable)          |一款android自动生成表格框架---An Android automatically generated table framework 
  [MPAndroidChart](https://github.com/PhilJay/MPAndroidChart)|Android图表控件MPAndroidChart的简单介绍(https://blog.csdn.net/ww897532167/article/details/77334345)
  
* 3 RecyclerView

  名称                                                                 |               描述  
  -|                                                                  -|  
  [BaseRecyclerViewAdapterHelper](https://github.com/GongHuixue/BaseRecyclerViewAdapterHelper)|BRVAH:Powerful and flexible RecyclerAdapter
  
  
## Android Utils
  名称                                                                 |               描述  
  -|                                                                  -|  
  [AndroidUtils](https://github.com/Blizzard-liu/AndroidUtils)|介绍各种libary的使用
  [AndroidUtils](https://github.com/haoma2012/AndroidUtils)|与Activity,APP,Convert,crash,File,image, Log, network,location, time,toast
  [android-utils](https://github.com/jingle1267/android-utils)|It contains most of the Android utility classes. 
  [Utils-master](https://github.com/huangshuyuan/Utils-master)|开发工具类封装
  [AndroidUtilCode](https://blankj.com/2016/07/31/android-utils-code/)|Android开发人员不得不收集的代码

## 优秀项目篇
  名称                                                                 |               描述  
  -|                                                                  -|  
  [Android_100_TOP-Projects](https://github.com/dinpay0188/Android-open-source-project)|Android开源优秀项目源码集合。
  [android-open-project](https://github.com/Trinea/android-open-project)|Android 开源项目分类汇总。
