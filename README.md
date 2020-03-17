# 安卓apk文件制作步骤

### 1. 安装java
下载Java安装到选定路径同时记住路径 

![image.png](https://upload-images.jianshu.io/upload_images/9443754-517383a890d58d8b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

（我则是把所有有Java相关文件的文件夹归纳在一起）

配置环境变量

在控制面板中打开环境变量或者是在电脑属性中打开

![image.png](https://upload-images.jianshu.io/upload_images/9443754-e34bad122f63cddf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

先是新建用户变量 Java_home 变量值为Java路径

![image.png](https://upload-images.jianshu.io/upload_images/9443754-4d576183c60787fe.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

则是编辑原有用户变量 path 在原有变量值后面加上 

![image.png](https://upload-images.jianshu.io/upload_images/9443754-1e99319930736d0d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

验证是否安装 打开cmd 使用Java -version命令查看自身Java版本 

![image.png](https://upload-images.jianshu.io/upload_images/9443754-3fa676c3b59dd355.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
### 2. 安装安卓开放平台
（1）下载sdk开发包

（2）下载 在目录中找到SDK manger.exe的应用程序 点击运行

![image.png](https://upload-images.jianshu.io/upload_images/9443754-a68f0677e148fc58.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/9443754-03b23d6af2cfddf9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 3.配置unity环境

1. 启动unity 打开edit 在下滑栏中找到 preferences

![image.png](https://upload-images.jianshu.io/upload_images/9443754-5a27f4db712a131c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

2 在preference菜单中 在左侧找到external tools 选择SDK（对应安卓开发平台） JDK对应（Java路径） browse浏览选择相对应的文件目录

![image.png](https://upload-images.jianshu.io/upload_images/9443754-783b8dcd51dbe20c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

3. 配置好之后 打开file下滑栏 找到 build setting 选项 进行配置

![image.png](https://upload-images.jianshu.io/upload_images/9443754-532968fb3efc814f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

4 首先 switch platform 适配安卓  之后 选择 add open scen 建立环境 勾选 

![image.png](https://upload-images.jianshu.io/upload_images/9443754-532968fb3efc814f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

5 点击 player sitting 修改 other name中的 package name 将里面的内容 xxx.xxx.xx任意修改 之后点击build

![image.png](https://upload-images.jianshu.io/upload_images/9443754-5e8478d82e0e55ff.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

6.完成之后 点击 build 添加文件名 选择保存路径 打包成apk文件 

![image.png](https://upload-images.jianshu.io/upload_images/9443754-b45f4bd771d3f854.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

7.接下来 就直接 将打包好的apk文件投入相关设备进行试玩

![image.png](https://upload-images.jianshu.io/upload_images/9443754-a20fba5968edb40c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 4 . 录屏演示最后成品




