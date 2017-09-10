<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/cn/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/cn/">知识共享署名-非商业性使用-相同方式共享 3.0 中国大陆许可协议</a>进行许可。

# 请我杯咖啡

各位金主大大的支持是我持续改进最大的鼓励😍

<div style="position:relative">
  <div style="position:absolute;height:3px;width:100%;background:#fff"></div>
  <img alt="qr-alipay" src="http://7ls0pw.com1.z0.glb.clouddn.com/qr-alipay.jpg" width="350" height="414" style="margin-right:30px">
  <img alt="qr-wechat" src="http://7ls0pw.com1.z0.glb.clouddn.com/qr-wechat.jpg" width="350" height="414">
</div>

# 说明

基于本书的初衷，面试的时候对于面试者和面试官来说，这本书的价值在哪里？

* **针对面试者:** 以后遇到这个问题的考察再也不心虚，结合这本书涉及到的方方面面更有效地组织自己对于面试的准备。不要背这本书的内容，而是根据这本书提及的方方面面真正深入理解，有条件的话自己去实践（例如在协议部分，用fiddler或者tcpdump抓包分析）。把本书当成一个指南，按图索骥拓展自己的知识网络
* **针对面试官:** 这个问题以后还是可以问的（并不是所有人都那么有远见读这本书哈😝），不过这就要区分了，对方到底是在背还是真的对整个体系结构有认识。如果是在背的话，适时打断对方换问题或者在关键点上拓展（你不是了解HTTPS嘛，说说HTTPS的适用场景和价值呗）。不过我觉得也不必纠结，能把整个体系背下来又有自己的理解和实践也是一种学习能力的体现。

**Tip:** 这本书不能保证你可以轻松通过任何公司的面试，面试的问题也不可能局限于这一个，如果你只是想通过阅读这本书来通过面试那可能这本书不太适合你，书中索引的任何一个链接作为一个粗放流程的展示都更能满足你的需要。如果你是个充满好奇心的开发者，所谓不谋万世者不足谋一时，不谋全局者不足谋一隅，希望不是天天仅仅在拧螺丝钉，那么这本书就是一个不错的参考。

# 直接阅读

* [Github Pages在线版](http://vincenthou.github.io/what-happens-when-you-enter-url-in-browser/)
* [Gitbook在线版](https://vincenthou.gitbooks.io/what-happens-when-you-enter-url-in-browser/content/)

# 缘起

“在浏览器中输入地址后发生了什么”，这是一个广为流传的面试题，也是一个哪怕你背过也能够考察出面试者知识深广度的题目。这个简单的问题不同的人根据自己的知识体系会答出不同的效果，个人感觉也是很好的把整个web应用开发体系串起来的一个良好切入点。没有想要实现“高大全”，只是作为自己知识体系的一个总结和梳理。网上有一些总结和整理，包括github上的[高星repo](https://github.com/alex/what-happens-when),但是感觉还是有些简略，通过整理成当前的这本书希望能够对整个web系统有个 big picture 的视角。

# 声明

本文基于[What-happens-when 的中文翻译](https://github.com/skyline75489/what-happens-when-zh_CN)，同时也借鉴和参考了网上很多其他大神的总结文章，加入自己的理解和整理，一般会在每个引用的章节列出原文的参考出处，但仍然难免有遗漏之处。如果有侵权请告知，会及时处理。

# 参考

* [What-happens-when 的中文翻译](https://github.com/skyline75489/what-happens-when-zh_CN)

# 开发

## 安装CLI工具

```
npm install gitbook-cli -g
```

## 打开本地开发服务器

```
gitbook serve
```

## 参考

* [Setup and Installation of GitBook](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md)
