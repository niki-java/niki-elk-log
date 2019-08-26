# niki-elk-log

#### 介绍
niki-elk-log项目集成elk日志输出，包含日志输出，切面日志打印，日志链式查找traceRootId,兼容所有spring项目(包含dubbo项目)

#### 软件架构
软件架构说明:spring 


#### 安装教程

1. 下载包以后，找到com.niki.log.ServiceAcpect的第37行，修改切点，把切点com.niki.demo换成你自己的路径
2. 增加spring扫描包，@ComponentScan(value = {"com.niki.log", "xxxxx"}) com.niki.log是我的中间件项目的路径，xxx是你自己的项目路径
3. 增加指定logback.xml配置，里面的输出路径自己去修改

#### 使用说明

1. 按照以上操作，启动项目就可以了，如果不知道可以加我微信: dcykefu 咨询。
2,因为日志已经自动打印了异常的日志，所以你们在controller层切记不要catch，直接throw就可以了。不要catch，直接throw就可以了。不要catch，直接throw就可以了。

#### 参与贡献

1. Fork 本仓库
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)