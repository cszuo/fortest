title: xcode6+ios8最新真机调试教程
date: 2014-07-25 02:06:42
tags: [XCode6]
categories: [趣味杂谈]
---
#ios项目最新真机调试教程

引言：众所周知，苹果的安全性做的一直很高，导致ios开发的门槛相对于安卓来说，高出不少，也就导致了现在iOS高级工程师一直是稀缺的资源。今天我们来谈一谈苹果的真机调试。

---
苹果的真机测试要复杂好多，最主要的是你需要花费99$购买苹果的开发者认证，其他的条件有：

- 一台测试手机或pad 
- 一台装有苹果系统的电脑

**具体步骤：**

1. 到官网https://developer.apple.com/，点击member center，用你刚刚购买的账号和密码登录,会看到如下所示的界面：

	![](http://mexiqq.qiniudn.com/img/xcode/1.png) 

2. 点击第一列，第二个图标（Certificates,Identifiers & Profiles）到如下界面:

	![](http://mexiqq.qiniudn.com/img/xcode/2.png) 

3. 点击IOS Apps众的任一个子项，进如如下界面：

	![](http://mexiqq.qiniudn.com/img/xcode/3.png)

4. 点击Certificates下面的呃All,右半部分会如上面那张图呈现，再点击右上角的＋号，跳到：

	![](http://mexiqq.qiniudn.com/img/xcode/4.png)

5. 将界面往下拉，会看到：

	![](http://mexiqq.qiniudn.com/img/xcode/5.png)

6. 点击蓝色字体World Developer Relations Certificate Authority,会下载如下文件：AppleWWDRCA.cer 文件

	![](http://mexiqq.qiniudn.com/img/xcode/6.png)

7. 双击该文件，打开如下界面，并现实安装了Apple worldwide Developer Relatios Cer….证书

	![](http://mexiqq.qiniudn.com/img/xcode/7.png)

8. 安装之后，在钥匙窜访问下，选择证书处理->从证书颁发机构请求证书

	![](http://mexiqq.qiniudn.com/img/xcode/8.png)

9. 点击....请求证书之后，跳到如下界面：

	![](http://mexiqq.qiniudn.com/img/xcode/9.png)

10. 如下填写：

	![](http://mexiqq.qiniudn.com/img/xcode/10.png)

11. 点击继续后,继续一路点下去，最后在桌面生成如下文件:CertificateSigningRequest.certSigningRequest
	
	![](http://mexiqq.qiniudn.com/img/xcode/11.png)

12. 好了，第一阶段已经完成，到第二阶段，接下来我们要做的就是在官网上将我们调试用的移动设备，还有调试用的电脑，调试的app 项目，以及购买的账户信息绑定到一起，生成几个证书，供Xcode和移动设备识别，用来进行真机测试

13. 再次到达如下的页面：

	![](http://mexiqq.qiniudn.com/img/xcode/12.png)

14. 选择Development 中的iOS App Development, 然后点击continue

	![](http://mexiqq.qiniudn.com/img/xcode/13.png)

15. 继续点击continue,知道出现如下界面：

	![](http://mexiqq.qiniudn.com/img/xcode/14.png)

16. 点击chose File ，将我们刚在再钥匙访问下生成的文件上传，进入如下界面点击Generate

	![](http://mexiqq.qiniudn.com/img/xcode/15.png)

	![](http://mexiqq.qiniudn.com/img/xcode/16.png)

17. 点击声称后跳到如下界面，点击download

	![](http://mexiqq.qiniudn.com/img/xcode/17.png)

18. 点击download之后将下载如下文件：ios_development.cer 然后双击安装

	![](http://mexiqq.qiniudn.com/img/xcode/18.png)

19. 将自己的设备添加到该开发者账号，点击Devices,再点击右上角的＋号
	
	![](http://mexiqq.qiniudn.com/img/xcode/19.png)

20. 点击之后进入如下界面，给自己的设备起一个名字（随便），下 面的UDID填写你要测试的那台真机的UDID 

	![](http://mexiqq.qiniudn.com/img/xcode/20.png)

	这里附上测试设备udid的寻找方法：打开iTunes，用鼠标点击一下ECID的位置就可以看到UDID了.

	如下所示：
	![](http://mexiqq.qiniudn.com/img/xcode/21.png)

	![](http://mexiqq.qiniudn.com/img/xcode/22.png)
21. 新建一个应用程序的识别ID：点击identifiers,点击右上角的＋号，到如下界面：
	
	在name出填写APP ID描述，一般是随便写，一直往下拉，在如下位置填写你的app ID,格式一般为com.*.*,其他默认，点击continue,submit
	![](http://mexiqq.qiniudn.com/img/xcode/23.png)
	
	![](http://mexiqq.qiniudn.com/img/xcode/24.png)

22. 绑定app mac 手机 和开发者账号：点击provisioning Profiles,再点击右上角的＋号，到如下页面
	![](http://mexiqq.qiniudn.com/img/xcode/25.png)

23. 选择ios App Development，然后点击continus,并在如下页面选择刚创建的app ID，点击contine
	![](http://mexiqq.qiniudn.com/img/xcode/26.png)

24. 上一步完成后跳到如下页面，绑定刚才的mac ,选则刚才生成的certificates,点击continue
	![](http://mexiqq.qiniudn.com/img/xcode/27.png)

25. 选择绑定的手机，点击continue
	![](http://mexiqq.qiniudn.com/img/xcode/28.png)

26. 给他起个名字，点击generate
	
	![](http://mexiqq.qiniudn.com/img/xcode/29.png)

27. 跳到如下界面，下载待会使用
	
	![](http://mexiqq.qiniudn.com/img/xcode/30.png)
	![](http://mexiqq.qiniudn.com/img/xcode/31.png)

28. 好的，这样账号上所有的操作完成，接下来只需要在mac  本地进行配置了，首先用Xcode 打开
	
	![](http://mexiqq.qiniudn.com/img/xcode/32.png)

29. 按图示打开
	![](http://mexiqq.qiniudn.com/img/xcode/33.png)

30. 进入如下画面，右键选中设备
	
	![](http://mexiqq.qiniudn.com/img/xcode/34.png)

31. 点击show provisioning profiles,进入如下界面
	
	点击＋号进行添加，将刚才下下来的如下文件，添加进去:
	![](http://mexiqq.qiniudn.com/img/xcode/35.png)
	![](http://mexiqq.qiniudn.com/img/xcode/36.png)
	添加之后，我们就只差最后一步，就可以真机调试了

32. 打开项目的 plist 文件，将右侧表中的不bundle identifier改为我们刚才设置的com.*.* (我的刚才是com.ljw.helloworld)
	
	![](http://mexiqq.qiniudn.com/img/xcode/37.png)

	![](http://mexiqq.qiniudn.com/img/xcode/38.png)
31. 好的，大功告成，我们终于可以开心的真机调试了

	![](http://mexiqq.qiniudn.com/img/xcode/39.png)
