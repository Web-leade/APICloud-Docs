/*
Title: 新浪微博平台接入
Description: 新浪微博开放平台接入
Sort: 11
*/

开发者在使用APICloud提供的来自第三方开放平台-新浪微博开放平台的相关模块时，需要开发者自行到新浪微博开放平台申请相应的appId（urlScheme），并将该appId以feature的形式配置到您项目的config文件中。

该appId的申请与您应用的创建过程有关，具体流程请参考如下介绍。


##申请步骤

- 登录新浪微博开放平台账号

访问新浪微博开放平台，访问地址：http://open.weibo.com

![图片说明](/img/docImage/70.png)

- 进入管理中心，若您未登录账号，微博开放平台将要求您登录：
 
![图片说明](/img/docImage/71.jpg)

- 完成登录即可，进入管理中心：

![图片说明](/img/docImage/72.jpg)

- 点击创建应用，选择微链接应用： 

![图片说明](/img/docImage/73.jpg)

- 进入微链接应用界面：

![图片说明](/img/docImage/75.jpg)
 
6、点击创建应用，在弹出框中选择“移动应用”：

![图片说明](/img/docImage/76.jpg)
 
进入移动应用创建界面：

![图片说明](/img/docImage/77.png)
 
- 填写基本信息，应用分类选择“客户端”，“手机”；应用平台勾选iPhone、Android。如下图：

![图片说明](/img/docImage/78.jpg)
 
- 点击创建即可。片刻页面将自动跳转至应用信息界面:
 
![图片说明](/img/docImage/79.jpg)

![图片说明](/img/docImage/80.jpg)
 
![图片说明](/img/docImage/81.jpg) 

![图片说明](/img/docImage/82.jpg) 

##必填信息获取：

**获取应用包名：**

Android平台的包名获取方式：

- 登录[APICloud云端](http://www.apicloud.com/login)，如下图：
 
![图片说明](/img/docImage/83.jpg) 

- 登录成功后进入应用概览界面，如下图：

![图片说明](/img/docImage/84.jpg) 

- 获取包名。在应用概览区域点击应用简介下方的小箭头，在下拉的区域中即可查看到本应用的包名、appKey、申请百度apiKey所需的SHA1安全码码值（百度key）等信息。如下图红色圈区域：
 
![图片说明](/img/docImage/84.png) 

将该包名填入应用包名即可。

**获取应用签名：**

- 创建应用过程中，需要输入应用签名。需要下载签名工具获取签名：

![图片说明](/img/docImage/85.jpg) 

 输入Android 包名，点击生成即可得到签名。
![图片说明](/img/docImage/86.png) 





- 输入完相关信息后，点击“保存以上信息”，等待审核即可：
 
![图片说明](/img/docImage/92.png) 

- 获取你需要的appId：

Android签名包名信息下的包含App Key字段的内容即为你需要的内容：

![图片说明](/img/docImage/93.png) 

将该appKey拷贝出来，审核通过后即可在你的新浪微博模块中使用。
