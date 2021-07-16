# Hugo版 WebStack 主题

本项目是基于**纯静态**的网址导航网站[webstack.cc](https://github.com/WebStackPage/WebStackPage.github.io) 制作的[Hogo](https://gohugo.io/)主题，主题安装后，将exampleSite目录下的文件复制到hugo站点根目录，网址信息可通过data目录下webstack.yml修改。

![](https://github.com/iplaycode/webstack-hugo/blob/master/static/assets/images/preview.gif)

这是一个开源的公益项目，你可以拿来制作自己的网址导航，也可以做与导航无关的网站。


应一些网友要求，尝试做了2.0版主题升级，主要基于[WordPress版主题](https://github.com/owen0o0/WebStack)，新增了聚合搜索框、夜间模式等，喜欢原版的网友请[下载1.0版主题](https://github.com/iplaycode/webstack-hugo/archive/refs/tags/webstack-hugo-v1.0.zip)

**2.0更新说明：**
+ 分类标题前面的图标升级为Font-Awesome-4.7.0，图标样式及名称可到[这里参阅](http://www.fontawesome.com.cn/faicons/)
```
另外需要将webstack.yml文件中icon：后方的名称做批量替换，linecons替换为fa
如：icon: linecons-star
变更为：icon: fa-star
```
+ 新增聚合搜索框、夜间模式，默认关闭
```
config.toml配置文件新增如下参数：

[params.search]
  enable = false
[params.darkmode]
  enable = false

如需开启搜索框或夜间模式，将相应的false改为true即可
```
