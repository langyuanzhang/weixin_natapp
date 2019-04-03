# weixin_natapp
使用natapp实现内网穿透，并利用微信测试号搭建本地微信开发

#### natapp下载
natapp官网地址：https://natapp.cn/ 下载，根据官网的1分钟快速新手图文教程 https://natapp.cn/article/natapp_newbie 进行操作即可。(注意要配置config.ini文件)

P.S. _购买隧道选择免费的就行，本地端口要根据项目运行时的具体端口设置_

![注意本地端口](images/duankou.png)

安装配置好后运行即可看到如下界面，中间的网址即是外网访问你本机的网址。由于选择的是免费隧道的，你关闭后再次打开是会动态变化的网址，未完成项目操作时千万别关闭，否则项目又要重新设置对应的网址

![natapp界面](images/natapp.png)

#### 微信官网文档
微信公众平台技术文档网址：https://mp.weixin.qq.com/wiki

#### 微信公众平台测试账号
网址 http://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/login 进入注册并登录。

###### 可获取测试号信息中的appID和appsecret，如下图所示：

![appID](images/appid.png)

###### 在测试账号中还要做好以下配置
1. JS接口安全域名修改
填入项目外网访问的域名地址

![appID](images/jsyuming.png)


2. 网页帐号修改
填入微信发送异步通知的回调地址

![appID](images/wangyezhanghao.png)

![appID](images/huidiao.png)

