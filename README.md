# qt-av-stream-player
Play stream(whatever ffmpeg can), based on [qt-av](https://github.com/wang-bin/QtAV)
Formats rtmp and http are supported.

### executable-green-version folder
You can directly use simpleplayer_sdk.exe in the executable-green-version folder. No need to compile the Qt-AV.
It will open the HongKong live: [rtmp://live.hkstv.hk.lxdns.com/live/hks](rtmp://live.hkstv.hk.lxdns.com/live/hks).

### source code 
It's an example in [Qt-AV repository](https://github.com/wang-bin/QtAV).
You have to install QT and Qt-AV first.

If you want to set the url opened to yours, just change the string of playerwindow.cpp, line 69.

**************************
### If you want to know more about using qt to develope a web stream player, please read this: [QT | 聊聊QT与直播流播放——从QMediaPlayer到Qt-AV](http://www.cnblogs.com/QingHuan/p/8830562.html)


