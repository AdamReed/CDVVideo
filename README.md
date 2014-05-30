# CDVVideo

NOTE:  修改了加载远程地址时如果按done按钮，视频会在后台继续播放的bug

## Description
CDVVideo is a Cordova/Phonegap 3.0+ plugin for iOS that allows playing video (local or remote) via a native video player. 

## History
This is a port of eiffelqiu's [https://github.com/eiffelqiu/phonegap-videoplayer-plugin](phonegap-videoplayer-plugin) done by bubblefoundry [https://github.com/bubblefoundry/CDVVideo](CDVVideo Cordova +1.7) which was then edited by wootwoot1234 to work with the Cordova/Phonegap 3.0+ command line interface.

## Installation

1. Using Phonegap CLI, in terminal navigate to your projects root directory.
2. run `phonegap local plugin add https://github.com/wootwoot1234/CDVVideo.git`
3. Play a video by calling `window.plugins.CDVVideo.play(video, portrait)`, where `video` is the URL or filename you wish to play and `portrait` is a string that is either `YES` or `NO`, indicating whether portrait or landscape orientation should be used.
4. _Optional:_ Change or overwrite `window.plugins.CDVVideo.finished(video)` to handle when a video finishes playing. `video` corresponds to the video that you passed to `window.plugins.CDVVideo.play()`.
