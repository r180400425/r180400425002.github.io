---
title: hexo_show_img
date: 2023-04-14 23:27:22
tags:
photos:
- /hexo-show-img/1.jpg
---

## 安装插件 hexo-asset-image

用管理员权限在cmd进行安装
![y](./hexo-show-img/chajian01.png)
本地显示图片成功，但是在网页中不能成功显示。
![y](./hexo-show-img/chajian01.png)
而巧妙的是，下面这种方式在vscode中不会显示图片，但是在页面可以成功显示。

{% asset_img chajian01.png 插件 %}
vscode的markdown显示效果如下
{% asset_img 3.png 页面显示效果 %}
页面显示效果如下
{% asset_img 2.png 页面显示效果 %}

end