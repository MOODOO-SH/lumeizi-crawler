##概述

这份脚本的主要任务是用来下载美丽妹子的图片，进而供收藏（是的，仅仅只是这个单纯的目的）用。程序猿以及码农平时孤苦零丁，需要找乐子。世界人民大团结万岁。

##关于 2B Json 接口

我把所有没有设防的私有 Json 数据请求接口统一称之为 2B Json 接口。请程序猿们注意，Ajax 请求私有数据接口的时候，如果不想让它被外界用来作爬取核心数据的系统漏洞的话，就给自己的接口加上防御用参数吧。

腾讯微博，新浪微博的某些页面上都有未设防的 2B Json 接口，我通过它们做到了很多官方给的接口不能提供的功能。这次爬取[卤妹纸](http://lumeizhi.com/)的大量妹纸图片，就是利用的 2B Json 接口。

获取 2B Json 接口的方法很简单，在页面上用 Chrome 的页面审查工具分析网络请求就可以了。

##使用方法

1. 让当前的环境中的 python 解释器是 2 版本的，而不是 python 3000
2. 使用 pip 安装依赖的 python module：pip install -r requirements.txt
3. 运行 lu.py，开爬（lu）：./lu.py

最后爬取的数据将会在 data 目录下保存好。

##TODO

还没想好。世界人民大团结万岁。
