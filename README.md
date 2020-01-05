# Unlock-netease-cloud-music

解锁网易云音乐客户端变灰歌曲

## 项目介绍

网易音乐相信不需要我过多的介绍大家也都知道，由于各种限制，相信很多人在听歌的时候也注意到了，很多的音乐呈现灰色的样式，是无法播放的，如下图所示。今天就带大家**把灰色**<span style="color:orangered;font-weight:bold;">不能听的音乐全部变成可以正常播放</span>**的音乐**，而且是 <span style="color:orangered;font-weight:bold;">全平台通用</span>哦！

![正常情况的网易云](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitDFAj3QFDPY6wNwsSxvk9Kgx37aYCoGutzyhfREnxVX9wHrzc7Vj8sPDNYdoHmFRgZETvzI3DjVMFeV73DHeYic!/r)

## 特性

- 使用 QQ / 虾米 / 百度 / 酷狗 / 酷我 / 咪咕 / JOOX 音源替换变灰歌曲链接 (默认仅启用一、五、六)
- 为请求增加 `X-Real-IP` 参数解锁海外限制，支持指定网易云服务器 IP，支持设置上游 HTTP / HTTPS 代理
- 完整的流量代理功能 (HTTP / HTTPS)，可直接作为系统代理 (同时支持 PAC)

## 使用方法

1.打开网易云音乐客户端，进入设置页面，设置自定义代理

- 自定义代理 ：填写服务器地址和端口号

- 代理服务器地址：127.0.0.1 （推荐本机搭建，速度快）

- 代理服务器端口：52000

  ![网易云端口设置](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitNVA*JJy7tiaoKq8AEZESmA8g63Bg7lqyJN4ajcwpKcs9JaMiUM6057gWYfdig6cUDrwA8LjiJ7WTTdms2gK8iM!/r)

**2.安装node.js**

官方网站：http://nodejs.cn/download/

下载后双击软件安装包打开安装，一直点下一步直到完成即可

![下载node教程](http://r.photo.store.qq.com/psb?/V13al3sI0DZH2X/uU1LfZtbAZh7BxNtJepksxyV1VxajpJrC*qs9L6CBVs!/r/dL8AAAAAAAAA)

3.**下载项目源码**

**https://github.com/meng-chuan/Unlock-netease-cloud-music.git**

下载后解压到任意文件夹,双击点开Unlock-netease-cloud-music文件夹中名为：网易☁🎵.bat 的文件

![运行脚本效果](http://r.photo.store.qq.com/psb?/V13al3sI0DZH2X/jP*9L3F**vfRcpTEE75xOfvRRNaIihXM5XD1UzLrAXM!/r/dL8AAAAAAAAA)

注：此窗口不可关闭，可以最小化

以后每次打开网易云先运行网易☁🎵.bat这个文件即可解锁所有灰色歌曲，在这里先恭喜你成功学会了第一种解锁网易云音乐灰色歌曲的方法

## <span style="color:orangered;font-weight:bold;">如果感觉上面的方法太繁琐，我这里还有第二种方案，无需下载任何资源，只需几步设置即可</span>

话不多说，直接上干活，我这里以win10为例，其他系统操作类似：

**第一步：鼠标左键点击桌面右下角的通知气泡**

![进入windows设置](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitMGJ7AgqvUrJRznTARdmR2EmIg3rtHCCPPNqVllA1zWgbIyfze0769Ldh.nohBLFqmTqE9x.5CcMjcQfQzMDC4s!/r)

**第二步：然后鼠标左键点击所有设置**

![进入windows设置](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitOQDcSdA1tqWNDHedWjIbfDaW24iVmP6fqjq34UKyvbziOz*0wHQviduIUZ51Xs7inPIv926TjLVKOfsxI732k8!/r)

**第三步：鼠标左键点击点击进入网络和intrnet**

![进入网络和intrnet](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitOWQdP2V3druIDzaKroBP1EUdDF3KKf7i75L9v6XlTOS9gpsdWUcqwZoqnZaFACIkv24vdSrooMClLwNm1yNN8o!/r)

**第四步，脚步地址：https://wy.ydlrqx.com/proxy.pac **

**操作步骤请直接看下图，都是使用鼠标左键点击**

![电脑代理设置](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitHwRx.079KCDHuhcOBT75xc2Ve3f1d*MXNfpaNcrH6wGwxS0yVWuiy0p8XPwC4SxFH3A3buyJJ2gSDTZuMK0mBI!/r)

**第五步，打开网易云音乐，进入设置，操作步骤见下图，都是使用鼠标左键点击**

![网易云代理设置](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitDQYs8Xq2483qZHJYIS8sgN6k6zKDkHBKLTBmgzqHQGy0BGb9vZROHxCiUGnpP7E9vG9.31bOXvrZ6KTddIX5zQ!/r)

最终效果如下:

![最终效果](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitJeP4B3MAL49KJwJS6gRSQa*VEybngZl06AyIvotAmkLBgk73BfhaOErOnJXQw1vF.1.744IWAHlko*NSum4sBY!/r)

PC端教程到此结束，喜欢我的作品请帮忙点个⭐，谢谢！！！

#  <span style="color:orangered;font-weight:bold;">接下咋们聊聊手机端</span>

**iOS端说明**

尝试了很多遍，就没成功过，放弃吧，各位果粉们！

**安卓端设置方法**

安卓手机型号太多，这里我使用小米6给大家演示，安卓端的使用必须要连接WiFi，否则无法使用，点击WIFi的详情，然后把代理选择为自动配置模式，同PC端一样，粘贴我提供的地址，记得保存！！！**地址：https://wy.ydlrqx.com/proxy.pac **

![安卓端代理设置](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitLmZTgA2d.b9PR3aMs3Wra*ChEwepvDYPOe.ZylZYCmxf7SZ97BtoX7*G24S39Q66*o1.3xkhw8DJSMvheHfDHE!/r)

接着再次打开网易云音乐大家就可以很清楚的看到如下图所示的效果，左侧是没有设置之前，很多音乐是灰色的无法试听和下载，右侧是设置后的，我们可以随意的试听和下载！

![安卓端最终效果](http://r.photo.store.qq.com/psc?/V13al3sI0DZH2X/L*Kej6uubMuzNnUMMkfitLQhCfV3n0g5pkMJOdVzkMqfG9N7dCwCRCErIDOrj0tygKfc7ryfHWw5Qkzt7jwVML6nGoA4U4mFc8stckbevvQ!/r)

手机端教程到此结束，喜欢我的作品请帮忙点个⭐，谢谢！！！

## 本教程仅用于学习交流，如有侵权请联系本人删除，禁止他人用于非法用途，转载请注明出处，谢谢！！！

**注：如加载缓慢可前往本人码云项目查看**https://gitee.com/meng-chuan/Unlock-netease-cloud-music