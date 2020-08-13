# cloud_game_core
This is a cloud mobile(arm64) game's solution. include server and client sdk.
The solution is realization on ROCKCHIP's rk3399 CPU, and run at Androd 9.0 OS.
The solution includes the following features:

1. server 
- screen capture   
- play sound capture   
- video encode to h264   
- audio encode to opus    
- remote control: receive client touch events and replay on system   

2. client
- decode h264 data and draw on screen
- decode opus data and playback
- hook user touch and send to server

## install description
1. server (need: rk3399, android 9.0)


2. client (any android mobile, need ver > 5.1)


## Cooperation description
This is a trial version with run time constraints.  
The solution is my own development, I have a full set of source code, if there are manufacturers need, can cooperate.   
Other versions of Android system can be transplanted.    
If you have any questions, please email me: yangyuqi@sina.com



# 云游戏核心解决方案
这是一款云游戏（arm64）的核心解决方案。包括服务器和客户端 sdk。
解决方案是在 ROCKCHIP 的 rk3399 CPU 上实现的，并运行在 Android9.0 操作系统上。

该解决方案包括以下功能：   
1 服务器
- 屏幕截图
- 播放声音捕捉
- 视频编码到 h264
- 音频编码到 opus
- 远程控制：接收客户端触摸事件并在系统上回放

2 客户端
- 解码 h264 数据并绘制到屏幕上
- 解码 opus 数据并回放到扬声器
- 拦截用户触摸事件并将这些事件发送到服务器

## 安装说明
1 服务器


2 客户端


## 合作说明
这套方案是我独自开发的，我有全套源码，如果有厂家需要，可以合作。   
对于其他版本的安卓系统可以进行移植。    
有任何问题可以给我发邮件：yangyuqi@sina.com

