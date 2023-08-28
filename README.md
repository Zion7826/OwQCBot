# OwQCBot

## 简介

**OwQC    [OwQ]**

OwQC是使用GOCQHTTP构成的机器人！支持多Q！ 

OwQC借鉴了KUM（大唐）/大唐等框架源码，也借鉴了PC协议框架的运行机制！

OwQC官方发行版带有兼容Kum和MyQQ的插件，欢迎体验！

版权所有/KUM、Daen、大唐、HIQQ、StarCatQQ、CCFUN（CCFUNSTUDIO）

交流社区 [OwQFUN社区](http://bbs.ccfun.com.cn/)  QQ交流群[1065271820](http://qm.qq.com/cgi-bin/qm/qr?_wv=1027&k=qBJoXQTHU1H3DigVRG9AoVze7ZviuoNg&authKey=NxKEUObmKeY76Ww0bTdxOH18DL7jb2fxZzE21rs0xv5VsWt9FZWNIkBM3UYNOKpB&noverify=0&group_code=1065271820)



## 声明

### OwQC Robot

- OwQC 完全免费并且开源发布，只适用于学习娱乐交流
- OwQC 不会以任何形式强制收费，请勿上当受骗 [官方平台只有QQ群 Gitee 社区]
- 非法使用/修改本项目内的源码/程序 所造成一切后果自负，与本项目开发贡献者无关

`OwQC` 采用 `AGPL-3.0` 协议开源 为了OwQC的未来考虑，我们**强烈建议**您做到以下几点：

- 二次修改/发布的程序不鼓励，不支持一切商用，收费行为

- 二次修改/发布的程序需要在显眼处保留原OwQC版权，不得扭曲或隐藏免费开源的事实
- 未经许可，任何人都不得使用OwQC的logo形象，不得以OwQC的名义做出未经许可的行为

## 使用
框架使用教程详细请见Q群1065271820

[GO-HTTP帮助中心](https://docs.go-cqhttp.org/)

## 原理

- 插件管理：参考了某些PC框架源码内的插件管理机制，并做出优化
- 事件接口：WS 接收事件 JSON解析   HTTP POST/GET 使用API功能
- 运行调用：将API功能封装至内部  HOOK owqcapi.dll E模块内打包调用DLL命令

## 开发

## 

```
注：打开源码若提示"程序加固段"请安装易语言助手开启模块保护，或者替换一下模块的引用
```

- 插件开发者：下载SDK，下载发行版文件，根据SDK内提示和模块内命令使用API命令
- 二次修改/发布框架：建议勿修改主体核心，SDK和OwQC后缀版权，以便OwQC系插件兼容通用

```
注：使OwQC系插件兼容通用，是为了方便“OwQC系列”插件在每一个“OwQC系列”的框架中能正常使用，方便用户操作，即同SDK
```

```
注：开源本框架是提供参考，内容太菜请大佬口下留情，开发者完全可以参考后独立写一个依赖于go-cqhttp的专项功能bot
```



## 发展

- [x] OwQC-windows-gocq-http
- [x] OwQC_SDK-E
- [ ] OwQC_SDK-Java/Python/C#/C++/······ 
- [ ] OwQC-More platforms
- [ ] OwQC-其他bot插件兼容 [敬请期待...]

## 鸣谢

> 感谢在OwQC成长中为OwQC提供帮助和建议的各大开发者以及用户们，谢谢你们 [Thanks♪(･ω･)ﾉ]
> 特别鸣谢：花米，Moh，Daen
> [GO-CQHTTP  GO-CQHTTP GO-CQHTTP  GO-CQHTTP  (YYDS)](https://github.com/Mrs4s/go-cqhttp)

## 补充
 > 您或许应具备一定的提问技巧 [没有任何人有任何理由无偿为您提供任何服务]
>
> 开放本框架源码是为了有更多参与到OwQC的开发维护中 欢迎参与到代码的优化维护更新中来
>
> [本人学业繁忙没有太多时间] [可以直接QQ私信留言给我您的新代码并且提供说明]
>
> 本项目纯属我的无聊易语言练手的东西 大佬不喜勿喷 也感谢您的选择和支持 
>
> [我最菜了呜呜呜] [淦，菜鸟不太会操作gitee怎么办] [我们接纳一切品行端正的开发者QAQ]
>
> [忘记了我还要说啥，等想到了再补充吧~]


                  ------模板来自Kum
