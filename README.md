### swoole websocket 实现html5直播
##### 直播的大潮下、我也赶上潮流、使用websocket swoole实现了直播功能、并将直播嵌套到了微信公众号当中
#### 实现思路
1)视频流的获取(H5当中有一个、具有一个调用摄像头获取视频的功能)
2)视频流的传输(使用swoole创建websocket服务器、进行传输)

**废话不多说直接上代码啦!!!!**
直播端:Laravel框架
微信观看端:Yaf框架
服务端: PHP源码
