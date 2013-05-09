android常用开源库分享
=================
   
   
这次就介绍了这些android开源库，各位有好介绍的可以私信我 [SinaWeiBo][15]
我的博客是[慕容博客][16]，欢迎来和我交流 
   
- ##异步ImageView
   
   > [android-smart-image-view][6]和[android-async-http][4]是同一个作者，这个是异步加载图片的imageview
   
   
- ## ImageCache 
- [Android-Universal-Image-Loader][8]   是一个图片缓存
   
   
   
   
- ##NewQuickAction
   > [NewQuickAction][7]这是一个基于popuwindw的功能提示view,结合Listview有很好的效果，不过有个不好的地方就是当功能里面的item只有一两个的是，会留黑边，需要自己优化
   
   ![Example Image](http://londatiga.net/images/quickaction1.png)  ![Example Image](http://londatiga.net/images/quickaction2.png) 


- ##ImageViewTouch  
  > [ImageViewTouch][9]这是一个用于查看图片的view，可以通过双指缩小拉伸控制图片大小，也可以通过双击控制图片缩放，有三个缩放大小等级，使用也很简单
  
  >          Matrix matrix = mImageView1.getDisplayMatrix();
  >         mImageView2.setImageBitmap( bitmap, matrix );
   
   
   
   
   
   
- ##awsome-3D-listview
   > [awsome-3D-listview][10]这是一个3D ListView
   
   
   
   
 - ##afinal
    > [afinal][11]是一个国人牛人的开源框架，
    > Afinal简介
    > Afinal 是一个android的sqlite orm 和 ioc 框架。同时封装了android中的http框架，使其更加简单易用；
    > 使用finalBitmap，无需考虑bitmap在android中加载的时候oom的问题和快速滑动的时候图片加载位置错位等问题。
    > Afinal的宗旨是简洁，快速。约定大于配置的方式。尽量一行代码完成所有事情。
    > 目前Afinal主要有四大模块：

    > FinalDB模块：android中的orm框架，一行代码就可以进行增删改查。支持一对多，多对一等查询。

    > FinalActivity模块：android中的ioc框架，完全注解方式就可以进行UI绑定和事件绑定。无需findViewById和setClickListener等。

    > FinalHttp模块：通过httpclient进行封装http数据请求，支持ajax方式加载。

    > FinalBitmap模块：通过FinalBitmap，imageview加载bitmap的时候无需考虑bitmap加载过程中出现的oom和android容器快速滑动时候出现的图片错位等   现象。FinalBitmap可以配置线程加载线程数量，缓存大小，缓存路径，加载显示动画等。FinalBitmap的内存管理使用lru算法，没有使用弱引用（android2.3以后     google已经不建议使用弱引用，android2.3后强行回收软引用和弱引用，详情查看android官方文档），更好的管理bitmap内存。FinalBitmap可以自定义下载器，      用来扩展其他协议显示网络图片，比如ftp等。同时可以自定义bitmap显示器，在imageview显示图片的时候播放动画等（默认是渐变动画显示）。
   



- ##android-common-tookit
  > [android-common-tookit][12] 适用于Android项目的通用工具类的集合。
  > 使用范例
>
 >  Adapter
>
adapter包设计了三类Adapter（继承自官方的Adapter）：CommonAdapter、CommonPagerAdapter、HolderAdapter。
CommonAdapter适用于创建例如主界面功能菜单等不需要Item更新的布局。CommonPagerAdaptert为PagerView而设计，提供强制刷新功能。
HolderAdapter适用于ListView等大量数据显示。其中HolderViewFiller是整合HolderAdapter的辅助工具类。
ViewCreator是以上Adapter的核心接口，它提供一个统一的创建View、更新View、回收View等操作的接口。
Common
>
Encrypt
>
Resource
>
System


- ##android-uitableview
  > [android-uitableview][13]是一个仿制Iphone UI的view,界面效果不错
   
   ![UITableView](http://thiago.grem.io/img/github/uitable-view.png "UITableView")
![UITableView](http://thiago.grem.io/img/github/uitable-view3.png "UITableView")
![UITableView](http://thiago.grem.io/img/github/uitable-view4.png "UITableView")



- ##android-viewbadger
 > [android-viewbadger][14]是一个提示UI，可以用于显示在view的上下左右位置
  ![Demos](http://www.jeffgilfelt.com/viewbadger/vb-1a.png "Demos")&nbsp;
![ListAdapter](http://www.jeffgilfelt.com/viewbadger/vb-2a.png "ListAdapter")

- ##瀑布流
   瀑布流开源的有两个，一个是基于ListView更改的，一个是基于LinearLayout
    - 基于[LinearLayout][1]的 
    >实现了类似于迷尚android和蘑菇街android的瀑布流布局，这个瀑布流问题有点大，慎用，开发者本身已经放弃维护，下面那个就是他基于里一个更改的
    
    ![Screenshot](https://github.com/dodola/android_waterfall/raw/master/screen1.png) ![Screenshot](https://github.com/dodola/android_waterfall/raw/master/screen2.png)
    
    
    - 基于[ListView][2]的
   > 这个是基于类似ListView的adpter,这个是在[PinterestLikeAdapterView][3]基础上改的，是一个韩国人写的，没用过，问题不多
   第一个是韩国人写的瀑布流效果截图，后面是三个是这个作者的截图
     ![Screenshot](http://cloud.github.com/downloads/huewu/PinterestLikeAdapterView/screenshot.png) ![Screenshot](https://github.com/dodola/PinterestLikeAdapterView/raw/master/01.png) ![Screenshot](https://github.com/dodola/PinterestLikeAdapterView/raw/master/02.png) ![Screenshot](https://github.com/dodola/PinterestLikeAdapterView/raw/master/03.png)
   
   
   
- ##http请求封装包 - android-async-http   
   
   > [android-async-http][4]这个是对http请求的封装库，使用文档在[传送门docs][5]使用很方便、简单，可以直接在UI上使用网络请求，如：
   
   >      AsyncHttpClient client = new AsyncHttpClient();    
   >      client.get("http://www.google.com", new AsyncHttpResponseHandler() {    
   >    
   >      @Override
   >      public void onSuccess(String response) {
   >         System.out.println(response);
   >      }
   >     });


声明
---
原创文章，转载请注明出处 慕容博客  http://www.mk5i.com ，thx



[1]: https://github.com/inmyfree/android_waterfall
[2]:https://github.com/dodola/PinterestLikeAdapterView
[3]:https://github.com/huewu/PinterestLikeAdapterView
[4]:https://github.com/loopj/android-async-http
[5]:http://loopj.com/android-async-http/
[6]:https://github.com/loopj/android-smart-image-view

[7]:https://github.com/inmyfree/NewQuickAction
[8]:https://github.com/nostra13/Android-Universal-Image-Loader
[9]:https://github.com/inmyfree/ImageViewZoom
[10]:https://github.com/inmyfree/awsome-3D-listview   
[11]:https://github.com/inmyfree/afinal 
[12]:https://github.com/chenyoca/android-common-tookit
[13]:https://github.com/inmyfree/android-uitableview

[14]:https://github.com/jgilfelt/android-viewbadger

[15]:http://weibo.com/131426520

[16]:http://wwww.mk5i.com

License
-

MIT

*Free Software, Fuck Yeah!*









