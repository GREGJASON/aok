# 安卓apk文件制作步骤
## 安装环境
### 1.1 安装java
下载Java安装到选定路径同时记住路径 

！[image.png] （https://upload-images.jianshu.io/upload_images/9443754-517383a890d58d8b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240）
（0）
配置环境变量

在控制面板中打开环境变量或者是在电脑属性中打开

先是新建用户变量 Java_home 变量值为Java路径

则是编辑原有用户变量 path 在原有变量值后面加上 

验证是否安装 打开cmd 
 
使用Java -version命令查看自身Java版本 

### 2. 安装安卓开放平台
（1）下载sdk开发包

（2）下载 在目录中找到SDK manger.exe的应用程序 点击运行
![image.png](https://upload-images.jianshu.io/upload_images/9443754-a68f0677e148fc58.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![image.png](https://upload-images.jianshu.io/upload_images/9443754-03b23d6af2cfddf9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 配置unity环境
1. 启动unity 打开edit 在下滑栏中找到 preferences

2 在preference菜单中 在左侧找到external tools 选择SDK（对应安卓开发平台） JDK对应（Java路径）

3. 打开案例 
