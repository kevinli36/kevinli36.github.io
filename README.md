博客的搭建教程修改自 [Hux](https://github.com/Huxpro/huxpro.github.io) 和 [BY Blog](http://qiubaiying.vip/)。

### 撰写博文

要发表的文章以 **Markdown** 的格式放在`_posts/`

yaml 头文件长这样:

```
---
layout:     post
title:      
subtitle:   
date:       
author:     
header-img: 
catalog: 	 
tags:
    - iOS
    - 定时器
---

```

### Keynote Layout

HTML5幻灯片的排版：

![](https://camo.githubusercontent.com/f30347a118171820b46befdf77e7b7c53a5641a9/687474703a2f2f6875616e677875616e2e6d652f696d672f626c6f672d6b65796e6f74652e6a7067)

这部分是用于占用html格式的幻灯片的，一般用到的是 Reveal.js, Impress.js, Slides, Prezi 等等。

其主要原理是添加一个 `iframe`，在里面加入外部链接。你可以直接写到头文件里面去，详情请见下面的yaml头文件的写法。

```
---
layout:     keynote
iframe:     "http://huangxuan.me/js-module-7day/"
---
```

iframe在不同的设备中，将会自动的调整大小。保留内边距是为了让手机用户可以向下滑动，以及添加更多的内容。


### 致谢

1. 这个模板是从这里 [Hux](https://github.com/Huxpro/huxpro.github.io) fork 的, 感谢这个作者。 
2. 感谢 Jekyll、Github Pages 和 [BY Blog](http://qiubaiying.vip/)。

### License

遵循 MIT 许可证。有关详细,请参阅 [LICENSE](https://github.com/kevinli36/kevinli36.github.io/blob/master/LICENSE)。

