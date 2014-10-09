BaiduGeolocationPlugin
======================

百度定位插件，兼容 w3c 的 geolocation 标准。

使用方法
--------

### window.geolocation.getCurrentPosition(success, error, options);
获取当前位置

### window.watchPosition(success, error, options);
持续追踪位置变更

### window.clearWatch(watchId);
清楚位置追踪

安装方法
-------

```
cordova plugin add https://github.com/gengen1988/BaiduGeolocationPlugin.git --variable ACCESS_KEY={{your access key}}
```
