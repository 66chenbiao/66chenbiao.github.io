---
layout: post
title: 搭建个人的GitHub博客
categories: GitHub
description: 搭建个人的GitHub博客
keywords: 个人博客, GitHub
---

本文讲述了如何从创建代码仓库到应用博客模板的详细步骤。

# 日志
从2018年注册了CSDN账号后，陆续续写了一些博客，但大部分都是上网查资料解决的，防止忘记用博客记录。网上找不到的解决方案，自己独立解决并写完发布的博客都能得到大家的认可。这说明原创实属不易，前人走过的坑，让后人少走弯路。2021-10-12，我完成了在GitHub上写博客的小愿望，至少不用接收外界的广告。

搭建GitHub博客的步骤：
a. 新创建一个个人仓库，可参考[知乎：会飞的猪](https://zhuanlan.zhihu.com/p/28321740)
b. clone[苜蓿鬼仙](https://github.com/jijiucheng/jijiucheng.github.io)的仓库，更换博客模板


1. 首先，不用多说，得先有一个GitHub账号吧：
![image](https://user-images.githubusercontent.com/44183747/136946826-05fbf2e1-b506-43a9-9bec-ee538db5d7f5.png)

填好自己得个人信息（用户名好像不能用汉字）：
![image](https://user-images.githubusercontent.com/44183747/136946883-123181fe-0263-4c00-a34f-bf8e7658e59e.png)

然后点击Create an account.
![image](https://user-images.githubusercontent.com/44183747/136946939-5a0e08b3-cb0e-4b3d-b90b-9c3c47228a4f.png)

这里选择免费的啦，然后Continue
![image](https://user-images.githubusercontent.com/44183747/136947001-21be32fa-ca57-4671-93d8-938989f2a474.png)

这里选择自己的一些基本情况，然后submit。
![image](https://user-images.githubusercontent.com/44183747/136947355-1490fb19-dfda-451c-9057-01b3ad809457.png)
最后来到这个界面就对了，点击右上角那个加号旁边那里，可以来到这个页面。

2.开始搭建博客：
以前GitHub上的项目之类的都是一大堆源代码，对于一个新手来说，看到一大堆源码，只会让人头晕脑涨，不知何处入手。他希望看到的是，一个简明易懂的网页，说明每一步应该怎么做。因此，github就设计了Pages功能，允许用户自定义项目首页，用来替代默认的源码列表。所以，github Pages可以被认为是用户编写的、托管在github上的静态网页。

首先，我们需要新建一个Repositories,Repositories就相当于一个库，存放我们的项目文件。
![image](https://user-images.githubusercontent.com/44183747/136947505-6dc7da69-120b-4a07-a26d-5f5bf9a64f07.png)

然后给自己的Repositories取一个名字，注意：名称格式最好为：用户名.github.io(如，66chenbiao.github.io)

然后点击create repositories.

随后跳转到该库界面,由于我是搭建好的，所以会有项目文件。
![image](https://user-images.githubusercontent.com/44183747/136947823-70db26f7-3946-476a-b967-6e86f1636447.png)

3.接下来，就该去下载GitHub桌面版了，为什么使用桌面版呢，因为简单，适合小白，没那么多命令行。官网下载可能有一些慢，这里是我下好的：链接：http://pan.baidu.com/s/1bpkzaKB 密码：mwgm。

下载下来后，打开用自己的用户名登录。然后选择File下的Clone repositories.
![image](https://user-images.githubusercontent.com/44183747/136948221-82abc2be-9b9a-4805-a1dc-f4d4fdf079bc.png)

然后将你刚刚建好的repositories的url复制过来，点击Clone。一般存放的默认文件夹为

C:\Users\计算机名\Documents\GitHub。

![image](https://user-images.githubusercontent.com/44183747/136948332-41596ab3-33d4-40c9-b68c-4bf7d2fd0bf7.png)
clone完之后你会发现C:\Users\计算机名\Documents\GitHub路径下多了一个文件夹，如图：
![image](https://user-images.githubusercontent.com/44183747/136948741-40651ac7-4f66-43ad-8401-51ca9fd09aba.png)

然后将该文件夹里的文件都删掉，如果有.git文件，需要保留.git文件

然后把[jijiucheng](https://github.com/jijiucheng/jijiucheng.github.io)仓库下载到本地，复制所有的文件到C:\Users\计算机名\Documents\GitHub路径下，如图：
![image](https://user-images.githubusercontent.com/44183747/136948396-07c3fe65-2315-471f-958d-953e4fbb1e42.png)

更改_config.yml、CNAME文件，[获取clientID和clientSecret](https://github.com/settings/developers)并修改。
![image](https://user-images.githubusercontent.com/44183747/136951120-7544bd7d-44d0-407c-bc45-c1d4bfc455a9.png)

![image](https://user-images.githubusercontent.com/44183747/136946464-fed4dda8-26e2-43e9-aff0-736ecbdafef8.png)


4.接下来改同步到网络上了，打开GitHub桌面版。你会发现有非常多的changes，如图：
![企业微信截图_16340386669998](https://user-images.githubusercontent.com/44183747/136949139-6170454b-082b-42a3-865a-4974985e1a6e.png)

然后，同步，点击如图所示区域。

注意：可能由于墙或者什么网络问题，上传有可能会失败或较久，需要多试几次。

然后回到GitHub网站上，你会发现该库文件下多了很多文件
![image](https://user-images.githubusercontent.com/44183747/136949257-09d38a64-62f6-4741-a625-2759201d216f.png)

到这里也就差不多了，可以输入地址(66chenbiao.github.io)访问自己的博客了，剩下的就该自己优化博客了。


我的个人CSDN博客：<https://blog.csdn.net/weixin_43849871?spm=1000.2115.3001.5343>，欢迎 点赞 和 收藏。





## 参考资料
[苜蓿鬼仙的搭建个人博客](https://juejin.cn/post/6844904135033110541)

[GitHub博客模板clone](https://github.com/jijiucheng/jijiucheng.github.io)

