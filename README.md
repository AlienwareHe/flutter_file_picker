# file_picker

基于[file_picker插件](https://github.com/miguelpruivo/flutter_file_picker)重新修复的插件。    
FIX问题：
1. MacOS上选择文件后获取到的路径为/的问题

## Getting Started

具体使用请参考: https://github.com/miguelpruivo/flutter_file_picker/wiki

如何开发一个go-flutter-desktop插件请参考：    
[官网地址](https://github.com/go-flutter-desktop/go-flutter/wiki/Create-a-hover-compatible-plugin)

如何在不发布Flutter插件的情况下修改一个开源Flutter插件请参考：

## 发布流程
1. git add/commit/push
2. git tag go/${version} (the version number in the pubspec.yaml file.)
2. execute cmd `hover publish-plugin`