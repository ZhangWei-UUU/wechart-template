# wechart-template

作为一个微信开发的练习Demo 本应用将会测试微信开发的各个点，在微信开发的世界里[微信公众平台](https://mp.weixin.qq.com/)是所有的核心基地。

微信开发的账户分为三个大类：

1. [服务号](https://mp.weixin.qq.com/wiki?t=resource/res_main&id=mp1445241432)
2. [订阅号](https://mp.weixin.qq.com/wiki?t=resource/res_main&id=mp1445241432)
3. [小程序](https://developers.weixin.qq.com/miniprogram/dev/index.html)

由于订阅号的权限很小，而小程序又基于服务号，所以本案例会基于服务号进行开发。开发者需要注意的是，服务号是作为企业服务只用，对于很多个人开发者而言在没有企业营业执照的情况下是无法通过微信认证，也无法调用微信自带接口。针对这个问题微信提供了一个沙盒账户，通过沙盒账户可以进行测试性项目开发练习。

第一步：[登录](http://mp.weixin.qq.com/debug/cgi-bin/sandbox?t=sandbox/login)

