![](https://github.com/HotBitmapGG/OhMyBiliBili/blob/OhMyBiliBili/art/bg.png?raw=true)

## OhMyBiliBili

[![Wercker](https://img.shields.io/badge/Android%20Client-OhMyBiliBili-brightgreen.svg)]() [![Wercker](https://img.shields.io/badge/Gradle-2.1.3-brightgreen.svg)]() [![Wercker](https://img.shields.io/badge/version-V2.1.5-brightgreen.svg)](https://github.com/HotBitmapGG/OhMyBiliBili) [![TeamCity CodeBetter](https://img.shields.io/teamcity/codebetter/bt428.svg?maxAge=2592000)]() [![Crates.io](https://img.shields.io/crates/l/rustc-serialize.svg?maxAge=2592000)]()

## 介绍

### 使用到的开源库

* 1.Rxjava，RxAndroid，Rxbinding，Rxlifecycle，RxBus。
* 2.Okhttp,Retrofit。
* 3.ijkplayer,烈焰弹幕库。
* 4.butterknife,Glide。
* 5.materialsearchview,FlycoTabLayout。


### 目前完成的功能

* 1.首页六大模块，推荐，番剧，直播，关注，分区，发现的实现。
* 2.热门视频排行榜，全区视频排行榜。
* 3.视频详情界面，视频评论，使用ijkplayer完成的视频播放，烈焰弹幕库实现的弹幕功能。
* 4.番剧，专题详情界面，番剧放送表，番剧索引。
* 5.使用ijkplayer实现的直播视频的播放。(直播的弹幕没有实现，暂时还抓不到弹幕的数据)
* 6.分区视频查看功能，目前只有基本的9大分区的实现，但是该接口需要Appkey才能获取到。
* 7.游戏中心，离线缓存的界面实现。
* 8.全区搜索的实现，目前支持综合视频，番剧，话题的搜索。
* 9.仿B站登录的小彩蛋。(登录只是假登录，随意输入帐号密码即可)
* 10.其他的一些仿官方的实现细节等，请自行发现。

### 未完成的功能
* 主题切换，准备使用B站自家的**[MagicaSakura](https://github.com/Bilibili/MagicaSakura)**
* 应用推荐。
* 直播功能的完善，横竖屏切换。
* 屏幕适配，版本适配。
* 番剧详情界面实现。
* 离线缓存的功能实现，视频下载到本地。


## 接口文档

* BiliBili API / REST service written in Go
[WhiteBlue](https://github.com/WhiteBlue)/**[bilibili-go](https://github.com/WhiteBlue/bilibili-go)**

* bilibili官方文档搬运(官方文档已不对外开放)
[fython](https://github.com/fython)/**[BilibiliAPIDocs](https://github.com/fython/BilibiliAPIDocs)**


## AppKey

关于Appkey的问题，如果你有AppKey,放置到Secret中即可，目前项目中有分区，番剧放送表等接口需要Appkey才能正常请求。


## 说明

由于该项目是业余时间开发，更新比较慢还请见谅，有任何意见，bug，问题可以提issuse，我会第一时间关注并解决。


## 更新日志

>由于每个版本更新的东西较多，所以从现在开始每个版本都会贴上更新日志.

### V2.1.5

  * 1.增加全区排行榜界面
  * 2.游戏中心数据界面更新

### V2.1.4

  * 1.使用ijkplayer替换掉Vitamio
  * 2.完成视频播放界面
  * 3.删除无用的资源文件
  * 4.屏幕适配工作

### V2.1.3

  * 1.主页推荐界面优化
  * 2.增加主页界面错误处理
  * 3.增加直播送礼物特效动画


## 截图

<a href="art/01.png"><img src="art/01.png" width="40%"/></a> <a href="art/02.png"><img src="art/02.png" width="40%"/></a>

<a href="art/03.png"><img src="art/03.png" width="40%"/></a> <a href="art/04.png"><img src="art/04.png" width="40%"/></a>

<a href="art/05.png"><img src="art/05.png" width="40%"/></a> <a href="art/06.png"><img src="art/06.png" width="40%"/></a>

<a href="art/07.png"><img src="art/07.png" width="40%"/></a> <a href="art/08.png"><img src="art/08.png" width="40%"/></a>

<a href="art/09.png"><img src="art/09.png" width="40%"/></a> <a href="art/10.png"><img src="art/10.png" width="40%"/></a>

<a href="art/11.png"><img src="art/11.png" width="40%"/></a> <a href="art/12.png"><img src="art/12.png" width="40%"/></a>

<a href="art/13.png"><img src="art/13.png" width="40%"/></a> <a href="art/14.png"><img src="art/14.png" width="40%"/></a>

<a href="art/15.png"><img src="art/15.png" width="40%"/></a> <a href="art/16.png"><img src="art/16.png" width="40%"/></a>

<a href="art/17.png"><img src="art/17.png" width="40%"/></a> <a href="art/18.png"><img src="art/18.png" width="40%"/></a>

<a href="art/19.png"><img src="art/19.png" width="40%"/></a> <a href="art/20.png"><img src="art/20.png" width="40%"/></a>

<a href="art/21.png"><img src="art/21.png" width="40%"/></a>

![](https://github.com/HotBitmapGG/OhMyBiliBili/blob/OhMyBiliBili/art/22.png?raw=true)





## Other

  * 知了日报客户端: https://github.com/HotBitmapGG/RxZhiHu

  * 高仿BiliBili客户端: https://github.com/HotBitmapGG/OhMyBiliBili

  * Gank.io客户端: https://github.com/HotBitmapGG/StudyProject

  * 妹子福利App: https://github.com/HotBitmapGG/MoeQuest

  * 圆环进度条: https://github.com/HotBitmapGG/RingProgressBar

  * 仿芝麻信用分仪表盘: https://github.com/HotBitmapGG/CreditSesameRingView

## License

 Copyright 2016 HotBitmapGG

 Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

 http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.





