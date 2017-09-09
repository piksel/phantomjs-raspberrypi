# [PhantomJS](http://phantomjs.org) for Raspberry Pi

PhantomJS binary for Raspberry Pi.  
Compiled on Raspbian Hardfloat.

Instruction set: __armv6__ (compatible with all raspberry pi devices)

__Note__: Due to different versions of libraries for Rasbian Stretch, you'll have to use the [stretch branch](https://github.com/piksel/phantomjs-raspberrypi/tree/stretch).

__2017-09-09__: Compiled 2.1.1 for Raspbian Stretch  
__2017-06-26__: Compiled the first qt5 version: 2.1.1  
__2014-11-18__: Updated to a freshly compiled 1.9.8 (latest as of writing this).

__Dependencies__:
`libicu52`, `libssl1.0.0`, `gstreamer0.10-base`, `fontconfig`, and `freetype2`

To install them:  
`sudo apt install libicu52 libssl1.0.0 gstreamer0.10-base fontconfig freetype2`  
