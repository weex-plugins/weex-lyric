# weex-lyric
weex-lyric是一个weex插件，可以通过weexpack快速集成，可以丰富weex功能

支持的weexpack版本： >= 0.2.0
支持的WeexSDK版本： >= 0.10.0

![image](./playground/device-2017-10-03-114539.png)

# 功能

# 快速使用
- 通过weexpack初始化一个测试工程 weextest
   ```
   weexpack create weextest
   ```
- 添加ios平台
  ```
  weexpack platform add ios
  ```
- 添加android平台
  ```
  weexpack platform add android
  ```
- 添加插件
  ```
  weexpack plugin add weex-lyric
  ```
# 项目地址
[github](https://github.com/weex-plugins/weex-lyric)

# 已有工程集成


## 安卓集成插件weexlyric
- 命令行集成
  ```
  weexpack plugin add weex-lyric
  ```
- 手动集成
  在相应工程的build.gradle文件的dependencies中添加
  ```
  compile '${groupId}:weexlyric:{$version}'
  ``` 
  注意：您需要自行指定插件的groupId和version并将构建产物发布到相应的依赖管理仓库内去（例如maven）, 您也可以对插件的name进行自定义，默认将使用插件工程的名称作为name


## iOS集成插件WeexLyric(还没添加iOS支持，待续)
- 命令行集成
  ```
  weexpack plugin add weex-lyric
  ```
- 手动集成
  在podfile 中添加
  ```
  pod 'WeexLyric'
  ```


  
