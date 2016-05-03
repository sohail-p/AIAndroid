
                                          FBI warning


		federal law provides severe civil and criminal penalties for the unauthorized reproduction,
		distribution ,or exhibition of copyrighted motion pictures (title 17,united states code,sections 501 and 508),
		the federal bureau of investigation investigates allegations of criminal copyright infringement 
		(title 17,united states code,section 506)`

# AIAndroid is:
一个开源Android聊天框架，使用RecyclerView实现。<br/>
已知在Android 5.0以下的系统的Dialogue会出现透明度的bug，在Android 2.0以下按钮好像没一个按得动。<br/>
我猜是CardView的锅。。

### 当前嵌入的业务逻辑：[城堡游戏](https://github.com/ice1000/Castle-game)

### 写AIAndroid的初衷:
受[我的友人](https://github.com/Wimacs)的影响决定开始写。<br/>
![icon](./app/src/main/res/mipmap-xhdpi/ic_launcher.png)<br/>
就是不知道这个和二次元的微妙结合会有什么样的效果呢<br/>
不同版本时期我也为本APP截了图，<br/>
在下面历史更新里面可以看到唷

## 声明
1. 由于本人同时是苦逼天朝学生党的一员和最后一届理科生， ~~所以本项目可能会太监。~~已经太监了
1. 本项目完全开源，任何人可以下载源码进行个人研究，且不得将其用于商业用途。
1. 严禁未经原作者允许的情况下将本APP二次开发。

# 相关文档
1. [聊天界面的实现技巧](https://github.com/ice1000/dialogs/blob/master/%E9%80%9A%E7%94%A8raw/%E8%A3%85%E9%80%BC%E8%AE%BA%E6%96%87/Android%E5%BC%80%E5%8F%91%E4%B8%AD%E4%BD%BF%E7%94%A8RecyclerView%E5%AE%9E%E7%8E%B0%E8%81%8A%E5%A4%A9APP%E6%B6%88%E6%81%AF%E6%A1%86%E5%B7%A6%E5%8F%B3%E5%AF%B9%E9%BD%90%E7%9A%84%E6%95%88%E6%9E%9C.pdf)

# 实现情况：

## 算法(运行方式)部分

- [X] 起名字
- [X] 字符串分割
- [X] 分割支持圆角符号
- [X] 可以很轻松的嵌入业务罗逻辑
- [ ] 中文分词
- [ ] 机器学习
- [ ] ~~强AI（痴人说梦~~
- [ ] 人类情绪
- [ ] 颜文字(๑>؂<๑)۶和表情的处理。
- [ ] 更多可爱的逐帧动画。
- [ ] 帮主人给一本书写摘要（功能了已经是

## UI(视觉效果)部分
- [X] 一个简洁的开始界面
- [X] 一个侧滑菜单实现简单的功能跳转
- [X] 对话由RecyclerView组成
- [X] 用户发送的文字在右边，Saber发的文字在左边
- [X] 二人的发言颜色不同
- [X] 按钮点击反馈
- [X] 长按弹出窗口确认删除
- [X] 重命名弹出窗口
- [X] 触摸消息背景颜色改变
- [X] 触摸消息背景颜色改变动画
- [X] 沉浸式状态栏
- [X] 一个使用ListView的设置界面
- [ ] 更优美的消息删除动画

## 设计模式规划
> + 聊天记录保存在SQLite中
+ 知识保存在SQLite中
+ 个人信息保存在Preference中
+ 根据大脑的结构封装思考的几个类

# 本次更新

### 2016年2月3日 1.3.0.0 嵌入一个业务逻辑
1. 没错！我把Castle-game的业务逻辑搞进来喽~
工作量巨大！光是数据库那块就花了我很长时间！！

# 历史更新

### 2016年1月25日 1.2.1.0 终于修复了侧滑菜单点不动的bug
1. 修复侧滑菜单点不动的bug
1. 调整一下项目结构方便以后的开发
1. 修复设置界面闪退的bug

### 2016年1月24日 1.2.0.2
1. 优美地封装了[BaseActivity](https://github.com/ice1000/AIAndroid/blob/master/app/src/main/java/util/BaseActivity.java)！真棒！封装在各个Activity中都有体现，除了Dialog。。。
1. 将常量类T也封装到了BaseActivity，为了方便外部访问我还在外面继承了一个，将一些Activity中用不到的字符串封装了。

### 2016年1月24日 1.2.0.1 考完了，我却还在上课
1. 一些UI中参数的修改
1. Dialog有阴影了

### 2016年1月20日 1.2.0.0 期末考试如火如荼进行中，我却依旧在更新，而且是大更新
1. 把Saber改成了小律(又抠了一批图，工作量巨大)
1. 优化NavigationView
1. 开始界面优化

### 2016年1月18日 1.1.1.1 在线进行的更新
1. 更新README，让它看起来不那么傻逼（蜘蛛阿姨说的
1. 修复一个简单却致命的bug，这个bug让我糗大了，之前还发布，结果特么有bug![233](https://github.com/ice1000/dialogs/blob/master/raw/ice1000_0x00.gif)
1. 我收回前言，这个项目还是会持续更新！

### 2016年1月17日 1.1.1.0 重大更新
1. 主界面增加侧滑菜单
1. 侧滑菜单基本功能设置，留下一个坑：简化书
1. 由于虚拟机打不开了我也不知道能不能运行。。
1. 最近的更新质量越来越高了、、好兆头！
1. 在贴吧release了这个版本

### 2016年1月17日 1.1.0.4
1. 继续写Javadoc
1. 增加新功能的企划

## 2016年1月15日 1.1.0.3 ~~又没忍住更新了。。~~
1. 过滤空消息
1. 写了各个类的Javadoc（很辛苦！
1. 更改监听器设置方法
1. 增加大脑皮层的两种构造方法。
1. 更改类名（主脑改成大脑皮层，记忆改成边缘系统

## 2016年1月15日 1.1.0.2 ~~好像忍不住又更新了~~
1. 开始界面不那么~~猥琐~~了
1. 减少多余的动画

## 2016年1月13日 1.1.0.1 ~~从这次更新以后，短期暂停更新~~
1. 开始动画变得更~~猥琐~~了。
1. 主页的字更小了。
1. 又多了一些没用的图片。。
1. ~~本次更新完毕估计就是我弃坑的时候。~~
1. ~~所以说我现在已经齐此UI坑了。~~
1. 什么时候有了AI算法了，就继续更新AIAndroid！

## 2016年1月12日 1.1.0.0 ~~UI设计工作正式宣告结束！！~~
1. 更改了昨天遗留下的所有问题，颜色的问题全部改过，饱和度大大降低
1. 优化设置界面。
1. 这个从此以后好像除了算法之外没什么可更新的了。。<br/>
所以说。。。。<br/>
UI设计工作正式宣告完成！<br/>
欧耶！<br/>
昨天说的截图：<br/>
![233](https://github.com/ice1000/dialogs/blob/master/通用raw/screencut_0x02.png)
![2333](https://github.com/ice1000/dialogs/blob/master/通用raw/screencut_0x03.png)

## 2016年1月11日 1.0.3.2
1. 做了重命名，虽然还有点问题，但是不算bug，就是丑了，功能已经实现
1. 封装了“记忆”Memories类。
1. 更改部分背景颜色。反正最近在颜色上着手比较多。明天更新一张截图。

## 2016年1月11日 1.0.3.1
1. 把颜色改的更浅了
1. 把主角的绿色改成了灰白（这样的话那几个animator就没用了。。不过还是先留着）

## 2016年1月10日 1.0.3.0 重大更新
1. 成功把去除、分开的字符都封装成正则表达式字库放CONSTS里面，这也是是第一次用正则表达式。。
1. 修复了昨晚上发现的bug
1. 更改弹出窗口的布局
1. 增加清空记录时背景色的检查
1. 上次push忘记改版本号了。。。
1. 现在主脑正式封装完毕，MainActivity只负责更新UI、和主脑通信，主脑负责数据的处理。
和SQLite的通信也交由主脑全权负责。这特么才叫MVC啊！

## 2016年1月10日凌晨 1.0.2.0 重大更新
1. 改进程序结构，回复的算法被单独提了出来。
1. 让所有调用到主脑的Activity都必须实现BrainUsingActivity。
1. 主脑的控制反转，呼唤Activity更新数据。
1. 修复最新发送的消息无法删除的bug。
1. 更改发送键的大小。
1. 不过还是发现了新bug，不太好描述就不说了。

![233](https://github.com/ice1000/dialogs/blob/master/通用raw/screencut_0x01.png)

## 2016年1月10日凌晨 1.0.1.4
1. 修复了bug。现在可以拿出来玩了。
1. 将主界面的menu做成了单独的。
1. 背景颜色变化还有点问题。

## 2016年1月9日 1.0.1.3
1. 增加了刷新。
1. 增加了清空聊天记录。
1. 旧的消息记录已经可以删除了。最新发送的消息记录仍然不能删除！
1. 更改了很多颜色配置。

## 2016年1月8日 1.0.1.2
1. 突然发现重大bug！消息记录删除不掉！吓尿！！
1. 增加了[toolbar](https://github.com/ice1000/AIAndroid/blob/master/app/src/main/res/layout-v11/toolbar.xml)
1. 把fab删了改成toolbar的三个点(朋友的建议)

## 2016年1月8日 1.0.1.1
1. 写了[关于开发者](https://github.com/ice1000/AIAndroid/blob/master/app/src/main/res/layout/activity_about_me.xml)
1. 将本项目源码的github链接放上去了
1. 终于可以删除聊天记录了，修复一大堆bug

## 2016年1月7日 1.0.1.0 重大更新
1. 设置消息触摸监听事件，触摸后背景会变色
1. 各种与UI有关的值的修改
1. 增加了阅读github的Activity，并且内置fab

## 2016年1月6日 1.0.0.6
1. 修改圆角大小为5dp
1. 自动去掉消息末尾换行符和空格

## 2016年1月6日 1.0.0.5
1. 发送的消息存储在SQLite中
1. 因为SQLite没有boolean类型，所以在
[存取的时候](https://github.com/ice1000/AIAndroid/blob/master/app/src/main/java/database/SQLiteManager.java)
转换成整数
1. 开启界面增加了
[一个逐帧动画](https://github.com/ice1000/AIAndroid/blob/master/app/src/main/res/drawable/saber_shake.xml)

![233](https://github.com/ice1000/dialogs/blob/master/通用raw/screencut_0x00.png)

## 2016年1月6日 1.0.0.4
1. 实例化了适配器，现在可以互相发送消息了
1. 发送的消息左右对齐
1. 主色调确定为蓝色

## 2016年1月6日 1.0.0.3
1. 初步完成SQLite存储数据的系统。
1. 修改图标格式(体现圆角)。

## 2016年1月5日 1.0.0.2
1. 图标(不知为何采用了吾王)。
1. 简单的界面

## 2016年1月5日 1.0.0.1
1. 开始界面卖个萌。(>▽<)
