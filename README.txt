buzz2weibo - 同步Google Buzz到新浪微博
======================================

将Google Buzz上的每条消息以最佳的形式同步到新浪微博。

特性
----

* 同步文字，这个自然
* 将buzz中的第一个图片上传
* 同步地理坐标，如果有的话
* 如果buzz附有链接，或者是发自Google Reader，链接也被同步
* 每次运行缺省只同步3条，防止被新浪微博暂时封禁
* 如果会编程，activity/下从BuzzActivity派生一个类，可以个性化处理特定的源（比如你的博客）

运行条件
--------

这是一个在你自己的机器运行的程序，它不是一个网络服务，至少目前不是。

要运行buzz2weibo，必须满足如下条件

* 要有python 2.5（2.7?）以上环境
* 要能周期定时执行本程序，否则只能每次手工运行
* 有畅通的网络，不一般的畅通，你懂的

安装
----

下载、解压，完毕

当然用git clone会更舒服

配置
----

将config.py.sample复制为config.py，然后编辑config.py，详见里面的注释

运行
----

python buzz2weibo.py


建议
----

建议在Linux下使用，cron里设为每分钟执行一次


链接
----

主页： https://github.com/sunner/buzz2weibo
Bugs： https://github.com/sunner/buzz2weibo/issues
