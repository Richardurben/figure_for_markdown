# github上为markdown编辑图片新建的图床库

1. 在github创建repository

2. 利用github的windows客户端clone至本地

3. 将需要上传的文件放入本地的文件夹

4. 利用github的windows客户端commit

5. 网页浏览复制图片URL，如:

**https://github.com/zhanghlHUST/figureForMarkdown/blob/master/17_urllib_parse_urlparse.JPG**

变为：

**https://github.com/zhanghlHUST/figureForMarkdown/raw/master/17_urllib_parse_urlparse.JPG**

## for example

![my idol IU](https://github.com/Richardurben/figure_for_markdown/raw/master/idol/1257_5.jpg)

> 链接：https://www.jianshu.com/p/33eeacac3344

# 使用jsdeliver CDN 为github中的图片加速

> CDN的全称是Content Delivery Network，即内容分发网络，jsDelivr 是国外的一家优秀的公共 CDN 服务提供商，也是首个「打通中国大陆（网宿公司运营）与海外的免费 CDN 服务」，我们可以借此搭建一个免费、全球访问速度超快的图床。

* 经过jsdelivr CDN加速的图片：![加速](https://cdn.jsdelivr.net/gh/Richardurben/figure_for_markdown/idol/IU4.jpg)

* 没有经过加速的图片：![无加速](https://github.com/Richardurben/figure_for_markdown/raw/master/idol/IU4.jpg)

PS：图床限制50M大小，可使用picgo更改链接网址



