
---
title: 第一章：1.3
---


# Hello_World

新建第一个项目，了解项目的结构。

第一步：新建一个项目

![新建一个项目](http://i.imgur.com/5zwyDva.png)

第二步：选择最小的兼容版本号

![选择最小兼容版本号](http://i.imgur.com/ZKLxHd8.png)

第三步：选择要创建的活动页面，一般默认选第二个空页面

![选择要创建的活动界面](http://i.imgur.com/FHcftcb.png)

第四步：给活动以及布局起名字，一般也是默认

![给活动起名字](http://i.imgur.com/ZoPrehz.png)

最后打开的是创建好的项目：

![创建好的项目](http://i.imgur.com/tk0eNgU.png)

##Android studio中的Project项目结构

* 	.gradle	Gradle编译系统，版本由wrapper指定
* 	.idea	Android Studio IDE所需要的文件
* 	app 模块
	* 	build	编译后的文件存在的位置（包括最终生成的apk也在这里面）
	* 	libs	依赖的库所在的位置（jar和aar)
	* 	src	源代码所在的目录
	* 	src/main	主要代码所在位置（src/androidTest)就是测试代码所在位置了
	* 	src/main/assets	android中附带的一些文件
	* 	src/main/java	最最重要的，我们的java代码所在的位置
	* 	src/main/jniLibs	jni的一些动态库所在的默认位置(.so文件)
	* 	src/main/res	android资源文件所在位置
	* 	src/main/AndroidManifest.xml	AndroidManifest不用介绍了吧~
	* 	build.gradle	和这个项目有关的gradle配置，相当于这个项目的Makefile，一些项目的依赖就写在这里面
		proguard.pro	代码混淆配置文件
* 	build	代码编译后生成的文件存放的位置
* 	gradle	wrapper的jar和配置文件所在的位置
* 	.gitignore	git使用的ignore文件
* 	build.gradle	gradle编译的相关配置文件（相当于Makefile）
* 	gradle.properties	gradle相关的全局属性设置
* 	gradlew	在unix下的gradle wrapper可执行文件
* 	graldew.bat	在windows下的gradle wrapper可执行文件
* 	local.properties	本地属性设置（key设置，android sdk位置等属性），这个文件是不推荐上传到VCS中去的
* 	settings.gradle	和设置相关的gradle脚本 	
* 	External Libraries 项目依赖的Lib, 编译时自动下载的
