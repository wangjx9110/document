# Cordova (PhoneGap) 探索总结

## 目的
  
  由于在探索 Cordova 的时候遇到了很多坑, 在此做下总结和分享. 大家看到有错误或不好的地方欢迎指正哈.

## 简介

  PhoneGap 是一个用基于 HTML, CSS 和 JavaScript 的, 创建移动跨平台移动应用程序的快速开发平台. 它使开发者能够利用 iPhone, Android, Palm, Symbian, WP7, Bada 和 Blackberry 智能手机的核心功能 —— 包括地理定位, 加速器, 联系人, 声音和振动等, 此外 PhoneGap 拥有丰富的插件, 可以调用.

  Cordova 是贡献给 Apache 后的开源项目, 是从 PhoneGap 中抽出的核心代码, 是驱动 PhoneGap 的核心引擎.

## 环境搭建

  * 相应开发平台的 SDK 包

    由于目前使用 Windows 系统, 采用 Android SDK 包作为探索.

    Android 开发包需要 Java 作为支持, 所以 Java SDK 的安装也是必须的.

      * Java SDK

        地址: [ http://www.oracle.com/technetwork/java/javase/downloads/jdk7-downloads-1880260.html ]

        环境变量配置: 

        [新增] JAVA_HOME: JDK 安装路径 [ 例: D:\Java\jdk1.8.0_11 ]

        [添加] Path: %JAVA_HOME%\jre\bin; 

        <可用控制台 java 命令验证>
        
        [添加] Path: %JAVA_HOME%\bin;     

        <可用控制台 javac 命令验证>

      *Android SDK

        地址: [ http://developer.android.com/sdk/index.html ]

        环境变量配置:

        [添加] Path: 解压后的 sdk\platform-tools 路径 [ 例: D:\adt-bundle-windows-x86_64-20140702\sdk\platform-tools; ] 

        <可用控制台 adb 命令验证>

        [添加] Path: 解压后的 sdk\tools 路径 [ 例: D:\adt-bundle-windows-x86_64-20140702\sdk\tools; ] 

        <可用控制台 android 命令验证>
        

  * Cordova command-line interface (CLI)

    D:\apache-ant-1.9.4\bin;

  * Andriod 虚拟机优化 (Intel 虚化技术)

  * Chrome WebView 调试

## 事件支持

## 音频组件

 是否可以引用线上链接

### 参考文献

  [ http://baike.baidu.com/view/4157600.htm ]

  [ http://cordova.apache.org/docs/en/3.5.0/ ]

  [ http://stackoverflow.com/questions/17688030/html5-audio-on-apache-cordova-android-native-app ]


