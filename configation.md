> 注意项目基本配置

---

## 首先我们先来说说coco2dx的配置

新建一个工程,请参考 \[官网流程\] \(http:\/\/www.cocos.com\/docs\/native\/v3\/getting-started\/setting-up-development-environments-on-mac-with-xcode\/zh.html\)

但是这个新建的文件是一个空文件,如果要添加一些coco2dx或者要改引入的工程文件请注意!

头文件相关的目录配置在这里

![](/assets/Snip20161121_3.png)

这里给大家看一下这里是目录,还有就是具体工程的文件目录

![](/assets/Snip20161121_5.png)

![](/assets/Snip20161121_7.png)

`$(SRCROOT)/../../cocos2dx-310`

`$(SRCROOT)/../../cocos2dx-310/cocos`

`$(SRCROOT)/../../cocos2dx-310/cocos/base`

`$(SRCROOT)/../../cocos2dx-310/cocos/physics`

`$(SRCROOT)/../../cocos2dx-310/cocos/math/kazmath`

`$(SRCROOT)/../../cocos2dx-310/cocos/2d`

`$(SRCROOT)/../../cocos2dx-310/cocos/ui`

`$(SRCROOT)/../../cocos2dx-310/cocos/network`

`$(SRCROOT)/../../cocos2dx-310/cocos/audio/include`

`$(SRCROOT)/../../cocos2dx-310/cocos/editor-support`

`$(SRCROOT)/../../cocos2dx-310/extensions`

`$(SRCROOT)/../../cocos2dx-310/external`

`$(SRCROOT)/../../cocos2dx-310/external/chipmunk/include/chipmunk`

`$(SRCROOT)/../../cocos2dx-310/external/lua/luajit/include`

`$(SRCROOT)/../../cocos2dx-310/external/lua/tolua`

`$(SRCROOT)/../../cocos2dx-310/cocos/scripting/lua-bindings/manual`

`$(SRCROOT)/../../cocos2dx-310/cocos/scripting/lua-bindings/auto`

`$(SRCROOT)/../../cocos2dx-310/tools/simulator/libsimulator/lib`

`$(SRCROOT)/../../cocos2dx-310/tools/simulator/libsimulator/lib/protobuf-lite`

`$(SRCROOT)/../../cocos2dx-310/cocos/scripting/lua-bindings/manual/third_party/luaxml`

`$(SRCROOT)/../../cocos2dx-310/cocos/scripting/lua-bindings/manual/third_party/lfs`

`$(SRCROOT)/../../cocos2dx-310/cocos/platform/`

## 关于MRC部分

由于coco2dx使用的是向下兼容所以,主要就是MRC,之前我用的是block+inline的函数,但是发现一个很重要的问题!

