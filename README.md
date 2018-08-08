


参考：

[Android 启动APP时黑屏白屏的三个解决方案](https://www.cnblogs.com/liqw/p/4263418.html)

[解决Android首次启动APP时，显示空白页或者黑屏时间长的问题](https://blog.csdn.net/iwanttohitren/article/details/52450407)

黑白屏问题的原因


你会很奇怪，为什么有些app启动时，会出现一会儿的黑屏或者白屏才进入Activity的界面显示，但是有些app却不会如QQ手机端，

的确这里要做处理一下。这里先了解一下为什么会出现这样的现象，

其实，黑屏或者白屏这里并不是不正常，而是还没加载到布局文件，就已经显示了window窗口背景，黑屏白屏就是window窗口背景。


解决方案：

在启动页的theme设置windowBackground为启动页的图片就可以解决启动时白屏黑屏






