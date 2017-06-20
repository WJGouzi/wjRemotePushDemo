# wjRemotePushDemo
this is base on JPush SDK ! 
这是基于极光SDK的写的推送demo。

#### 一、集成极光的SDK

0.[SDK链接](https://www.jiguang.cn/downloads/sdk/ios/)

1.导入极光推送的demo中的Lib文件到工程中，

2.然后在工程中导入依赖库:

* CFNetwork.framework
* CoreFoundation.framework
* CoreTelephony.framework
* SystemConfiguration.framework
* CoreGraphics.framework
* Foundation.framework
* UIKit.framework
* Security.framework
* lib.tbd
* UserNotifications.framework
* libresolv.tbd

3.关闭bit code ： 

build settings  >> build options >> Enable Bitcode >> No

4.开启允许通知：

capabilities >> Push Notificaitons >> On

#### 二、证书的配置

对于ios的推送证书的配置需要在[苹果开发者中心](https://developer.apple.com/account/ios/certificate/?teamId=6UK4NFK9JE) 进行配置，详细的[介绍](http://www.jianshu.com/p/c2592540a335) 入文章所介绍的。

#### 三、基于极光的SDK开发

有关的开发见官方[文档](https://docs.jiguang.cn/jpush/client/iOS/ios_sdk/)。



