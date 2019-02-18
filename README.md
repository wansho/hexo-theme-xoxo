# hexo-theme-xoxo

[TOC]

Hexo theme inspired by [microb](https://github.com/microacup/hexo-theme-micorb) 

[Demo](https://blog.0xff000000.com)

Snapshots: 

![](http://7xr586.com1.z0.glb.clouddn.com/images/fbehv.png)

![](http://7xr586.com1.z0.glb.clouddn.com/images/kwyq1.png)

![](http://7xr586.com1.z0.glb.clouddn.com/images/og6jh.png)

...

## 特点

- 简约
- 对移动屏幕友好
- 名字骚气...
- 颜色搭配让人更容易集中注意力
- 编不下去了


## 使用
除了基础 Hexo 配置外,你还需要这样...

### _config.yml
```yml
# Custom Config
menu:
  home: /
  archives: /archives
  tags: /tags
  search: /search
  about: https://0xff000000.com
  rss: /atom.xml

search:
  path: search.xml
  field: post

#RSS feed https://github.com/hexojs/hexo-generator-feed
feed:
  type: atom
  path: atom.xml
  limit: 20
  hub:
  content_limit: 140


sitemap:
    path: sitemap.xml

disqus_shortname: XXX

google_analytics: XXX
baidu_analytics: FuckUBaidu

#footer
index_page: https://blog.0xff000000.com
main_site: https://0xff000000.com
github: https://github.com/KevinOfNeu

```

### tags 和 search 功能配置

由于时间有限，不能短时间内速成一个简约又不缺核心功能的主题，所以只能退而求其次，找一个自己满意的主题，然后修改。

主题地址：[Github Hexo-Theme-xoxo](https://github.com/KevinOfNeu/hexo-theme-xoxo)

主题Demo: https://blog.0xff000000.com/

注意：要实现 tags 和 search 两个功能，需要进行如下配置：

```
step1:
	hexo new page tags
	
step2:
	编辑 /source/tags/index.md，增加 type
	---
    title: tags
    date: 2016-06-08 16:19:38
    type: "tags"
    ---

search 同理，只需要将 tags 改成 search
	
参考：https://github.com/iissnan/hexo-theme-next/issues/339
```

### 增加百度统计

https://www.cnblogs.com/fazero/p/7976651.html

