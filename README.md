## MIDock
项目基于[MIUIDock](https://github.com/ouhoukyo/MIUIDock)项目二次开发  
一个xposed模块，将MIUI高斯模糊的搜索栏修改成Dock背景

### 模糊条件
+ Android 11 以上
+ `build.prop` 中 `ro.miui.backdrop_sampling_enabled = true`

### 使用前须知
1. 无论你使用的是哪个类xposed框架，请在设置内开启资源钩子
2. 本项目只适配最新的RELEASE版本，如果有Bug，请提交[issues](https://github.com/lamprose/MIDock/issues)，如果你使用的是ALPHA（内测）版本的桌面，请自行修改代码编译

### 使用方法
激活模块后重启系统桌面,打开桌面设置点击打开搜索栏再点击即可弹出模块设置弹窗
![preview-1](https://raw.githubusercontent.com/lamprose/MIDock/master/screenshots/preview-1.jpg)
![preview-2](https://raw.githubusercontent.com/lamprose/MIDock/master/screenshots/preview-2.jpg)

### 致谢
- [XposedBridge](https://github.com/rovo89/XposedBridge): the OG xposed framework APIs
- [LSPosed](https://github.com/LSPosed/LSPosed):LSPosed Xposed Framework.
- [MIUIDock](https://github.com/ouhoukyo/MIUIDock):一个xposed模块，将MIUI高斯模糊的搜索栏修改成Dock背景
- [EzXHelper](https://github.com/KyuubiRan/EzXHelper):一个使Xposed模块开发变的更轻松的kotlin库

### License
本项目基于[MIT](https://github.com/lamprose/MIDock/blob/master/LICENSE)协议开源