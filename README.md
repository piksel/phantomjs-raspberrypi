# [PhantomJS](http://phantomjs.org) for Raspberry Pi

PhantomJS binary for Raspberry Pi.  
Compiled on Raspbian Hardfloat.

Instruction set: __armv6__ (compatible with all raspberry pi devices)

__Note__: Due to different versions of libraries for Rasbian prior to Stretch, you'll have to use the [jessie branch](https://github.com/piksel/phantomjs-raspberrypi/tree/jessie).

__2020-02-09__: Added a [release with libicu57 included](https://github.com/piksel/phantomjs-raspberrypi/releases/tag/v2.1.1-r)  
__2017-09-09__: Compiled 2.1.1 for Raspbian Stretch  
__2017-06-26__: Compiled the first qt5 version: 2.1.1  
__2014-11-18__: Updated to a freshly compiled 1.9.8 (latest as of writing this).

__Dependencies__:
`libssl1.0.2`, `gstreamer0.10-base`, `fontconfig`, `freetype2` and (except for v2.1.1-r) `libicu57`

To install them:  
`sudo apt install libicu57 libssl1.0.2 gstreamer0.10-base fontconfig freetype2`  

or for [v2.1.1-rpi](https://github.com/piksel/phantomjs-raspberrypi/releases/tag/v2.1.1-r) (which should work with >= buster):  
`sudo apt install libssl1.0.2 gstreamer0.10-base fontconfig freetype2`
