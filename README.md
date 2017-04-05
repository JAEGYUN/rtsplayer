# rtsplayer
a very, very, very, very simple rtsp player using FFMpeg and ImageView.


## Install

```cordova plugin add https://github.com/felipew/rtsplayer.git```

Execute the compile.sh inside the Plugins folder

Now you are ready to go

## Using

``` javascript
cordova.plugins.rtsplayer.watchVideo("rtsp://10.0.0.100:554/video", callbackSucces, callbackError);
```

``` javascript
cordova.plugins.rtsplayer.watch("rtsp://10.0.0.100/video", "user", "password" callbackSucces, callbackError);
```

## Contribute

* General improvments
* Audio support on iOS


## About

This plugin was origanly created to be used with h.264 rtsp streams.


More info about ffmpeg/ios etc etc: [ffmpeg ios](http://www.cantgetnosleep.com/wordpress/?p=111)
