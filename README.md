# utils4s[![Build Status](https://travis-ci.org/jacksu/utils4s.svg?branch=master)](https://travis-ci.org/jacksu/utils4s)[![Join the chat at https://gitter.im/jacksu/utils4s](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/jacksu/utils4s?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

utils4s包含各种scala通用、好玩的工具库demo和使用文档，通过简单的代码演示和操作文档，各种库信手拈来。

**同时欢迎大家贡献各种好玩的、经常使用的工具库。**

[开源中国地址](http://git.oschina.net/jack.su/utils4s)

QQ交流群 `432290475`

## common库

[日志操作](log-demo)（[log4s](https://github.com/Log4s/log4s)）

[单元测试](unittest-demo)（[scalatest](http://www.scalatest.org)）

[scala学习用例](scala-demo)

[日期操作](lamma-demo)（[lama](http://www.lamma.io/doc/quick_start)）（注:只支持日期操作，不支持时间操作）

[日期时间操作](nscala-demo)（[nscala-time](https://github.com/nscala-time/nscala-time)）（注：没有每月多少天，每月最后一天，以及每年多少天）

[json解析](json4s-demo)（[json4s](https://github.com/json4s/json4s)）

[resources下文件加载用例](resources-demo)

[文件操作](file-demo)（[better-files](https://github.com/pathikrit/better-files)）

[单位换算](analysis-demo)（[squants](https://github.com/garyKeorkunian/squants)）

[线性代数和矩阵计算(breeze)](https://github.com/scalanlp/breeze)

[分布式并行实现库akka](http://akka.io)

[Twitter工具库](twitter-util-demo)（[twitter util](https://github.com/twitter/util)）

## BigData库
[spark streaming测试用例](sparkstreaming-demo)

[基于spark streaming的聚合分析(Sparkta)](https://github.com/Stratio/Sparkta)

[图处理(cassovary)](https://github.com/twitter/cassovary)

[基于spark进行地理位置分析(gagellan)](https://github.com/harsha2010/magellan)

## Pull Request流程
1. 首先 fork 我的项目
2. 把 fork 过去的项目也就是你的项目 clone 到你的本地
3. 运行 git remote add jacksu git@github.com/jacksu/utils4s.git 把我的库添加为远端库
4. 运行 git pull jacksu master 拉取并合并到本地
5. coding
6. commit后push到自己的库( git push origin master )
7. 登陆Github在你首页可以看到一个 pull request 按钮,点击它,填写一些说明信息,然后提交即可。
1~3是初始化操作,执行一次即可。在coding前必须执行第4步同步我的库(这样避免冲突),然后执行5~7既可。