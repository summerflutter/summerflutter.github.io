---
layout: post
title:  "First Step in Git and Jekyll"
date:   2016-10-20
excerpt: "My very first step in Git and Jekyll and try markdown"
tag:
- markdown 
- syntax
- sample
- test
- jekyll
comments: true
---

连续一个星期天天晚上在家折腾，今天突然发现如果不用local server其实根本不用那么麻烦，用已设定好的theme，学会如何改信息，还有会写markdown，就好了。
当然在local写会更快更有效，也不用一直commit。总地来说还是local比较方便——本地编辑，弄好之后上传就行。

第一篇日志得好好记录这几天我都是怎么折腾的。

## Install Jekyll
Windows系统其实并不方便，详细教程见下：
https://jekyllrb.com/docs/windows/#installation

第一部是安装Chocolatey，听上去很甜蜜？哦，并不！虽然只有一行指令，但我这个电脑白痴仍然花了至少半个多小时才弄好。

首先打开Cmd窗口，Copy Paste指令，不行，权限不够，需要administrator right。好，我换成PowerShell, 可是有两个该怎么办？那，我两个都试。怎么还是不成功？？于是上网查error message，好，输指令，换权限，但还是不行！

我耐心快到极限的时候，想到不是还可以用admin来开command窗口嘛！可是怎么开的来着？

哦，原来是`Win+X`。

接下来安装Ruby, Gem，还算顺利。

## First trial with GitHub
我首先搭建了第一个page，十分初步，只有一个`index.html`. 于是接下来开始研究上哪里找模板。

Jakyll的模板很全。第一个选好的模板非常漂亮，无奈一面只能显示三篇文章。想到之后要找文章得翻很久，并且每篇都得配图，我果断放弃了。

第二个模板很简洁，但我不知道如何管理标签——对我就是伸手党就是想模板上啥功能都有。于是第二个也放弃了。

找模板真的不容易啊，http://jekyllthemes.org/ 上面的模板挺多都很不错，一起有14面，但也没搜寻功能，只能一面面翻，一开就是十几个页面。

最终选了这个，开posts时一个一个显示的动画真的是很酷炫啊！

## First step on my blog
好的，接下来要开始写我的**第一篇日志**了。

可是，为啥生成出来的网页不对呢？

为啥人家的图方方正正地在中间，图标链接都好好待着，我的到处飞呢？

于是我从`index.html`找到`home.html`再找到`head.html`，终于发现`css`文件链接所在地，于是在`_config.yml`里改了信息，终于一切正常了。

再后来，稍微研究了一下`_posts`里的`markdown`文件，终于可以写第一篇日志了，就是这篇了。

## Next step
还有很多后续工作得完成：

* 解决jekyll在windows运行的`SSL_Connect`问题
* GitHub Desktop得用得更加熟练
* 改掉网站的图片，更私人化
* 最重要的，勤更新

