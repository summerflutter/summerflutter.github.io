---
layout: post
title:  "Second Step on Jekyll"
date:   2016-10-21
excerpt: "My second step on Jekyll"
tag:
- markdown
- jekyll
comments: true
---

昨天要locally run Jekyll, 无奈总是有一个`SSL_connect`问题。搜寻结果是因为certificate的问题，但确认之后所有的certificates都没有问题。

然后我简单粗暴地把报错信息之后的那个文件删了。

居然运行了。

这篇日志记录一下具体步骤，以防之后忘记。

### Applications to use: GitHub Desktop, Cmd, Markdown editor
首先，打开Github, 确认Git上的文件和本地文件是同步的（`Sync`）。

然后，就可以本地改文件。

如果要查看进度，在Cmd里进入所在文件夹，输入`jekyll serve`, 便可在本地域名里查看。

做好所有改动之后，需要push到Git里。打开Github desktop, 查看改动信息，写好Comment，然后Commit。别忘了`Sync`。

等一会会，就可以看到更新的网站了。
