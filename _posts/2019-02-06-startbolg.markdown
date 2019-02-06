---
layout:     post
title:      关于博客
subtitle:   在本地写博客然后同步
date:       2019-02-06
author:     jiale
categories: jekyll update
catalog: true
tags:
    - Blog
---
#####  过程记录
先将远程仓库clone到本地，进入仓库目录下  
	添加远程连接：  git remote add origin 仓库地址  
	本地和远程关联：git branch --set-upstream-to=origin/master master


然后安装好jekyll和依赖包后，进入仓库目录。执行命令 jekyll server，接着在文件夹_posts下创建markdown文件，使用MarkdownPad打开，使用markdown语言编辑博客。之前不知道关于这个文件名的格式应该是“xxxx-xx-xx-名称”，也就是“年-月-日-名称”。  

编辑完成后，在本地使用网址localhost:4000查看的，然后发现地址是这样的localhost:4000/jekyll/update/2019/02/05/。进入对应的文件夹发现发现最里面是一个index.html。稍微有点理解jekyll了，自动分析保存的的markdown文件，然后生成对应的html页面。  
还有很多不明白的，但是最基本的写博客已经可以进行了.慢慢来，每天进步一点点。

在git里使用	git add命令的时候，告诉我paths are ignored.最后使用 

	$ git add -A
就可以了。  

2019.2.6 17：45



	交流Email：1575996446@qq.com
