# hunoc

[English](./README.md)

## 介绍

hunoc 是一个基于[huno](https://github.com/letiantian/huno/)的一个响应式的Hexo主题.  
许可协议:[Mozilla 公共许可证 Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)  
为了满足一些需要,自己对huno进行了一些修改,算是第一个正经项目吧.  
自娱自乐地Commit,Release,写更新日志,嘛,做人最重要的是开心.  

## 项目状态

### 稳定版

[![GitHub release](https://img.shields.io/github/release/Riband/hunoc.svg?style=flat-square)](https://github.com/Riband/hunoc/releases/) ![GitHub Release Date](https://img.shields.io/github/release-date/Riband/hunoc.svg?style=flat-square)  

### 测试版

![GitHub (pre-)release](https://img.shields.io/github/release/Riband/hunoc/all.svg?style=flat-square) ![GitHub (pre-)Release Date](https://img.shields.io/github/release-date-pre/Riband/hunoc.svg?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/Riband/hunoc.svg?style=flat-square)  
huno版本: Commit-2693076 (2019-01-12)  

## 主要特性

### 继承自huno的特性(会有一些不同)

* 响应式主题设计
* Mathjax数学公式支持
* [Awesome_toc](https://github.com/letiantian/awesome-toc),一个为网页生成目录的小工具，也支持回到顶部的功能
* [GitHub仓库控件](https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget)
* 社交网站图标
* 独立的归档页面

### 新的特性

* 定制选项(custom)支持用额外的CSS自定义主题
* 支持在一些选项中使用HTML
* 透明外观
* 支持Vssue,Gitment,Gitalk三个基于Githun Issue的评论系统
* 更好的子目录支持,只需修改config.root
* 更灵活的主题选项,可以在多处配置

## 演示

[查看](https://riband.github.io/hunoc-demo/)  

[![hunoc Demo Img](https://riband.github.io/RiBase/hunoc-demo/demo.jpg)](https://riband.github.io/hunoc-demo/)  

## 如何使用

### 方案1: 下载解压(推荐)

1. 打开[最新稳定版发布页面](https://github.com/Riband/hunoc/releases/latest)
2. 下载 **Source code(zip)**
3. 解压至 &lt;你的hexo路径&gt;/themes/hunoc
4. 修改hexo的 _config.yml
    <pre>theme: hunoc</pre>
5. 如果有进一步的需要,编辑themes/hunoc/_config.yml,但建议将其中的选项复制到&lt;你的hexo路径&gt;/_config.yml中修改

### 方案2: 用Git克隆仓库

1. 启动 shell/cmd 进入你的hexo路径
2. 确保安装了git,然后执行:  
    git clone git://github.com/someus/hunoc.git themes/hunoc
3. 修改 hexo的 _config.yml
    theme: hunoc
4. 如果有进一步的需要,编辑themes/hunoc/_config.yml但建议将其中的选项复制到&lt;你的hexo路径&gt;/_config.yml中修改

## 主题选项

所有的选项都可以在/themes/hunoc/_config.yml,/_config.yml,/source/*.md中使用,有特殊注明的除外  
请以/theme/_config.yml中的说明为准  
<pre>
hc_post_comments: [String]/false
    false: 无评论功能  
    vssue: 使用vssue(需在hc_github_config进一步设置)
    gitment: 使用gitment(需在hc_github_config进一步设置)
    gitalk: 使用gitalk(需在hc_github_config进一步设置)
    manual: 在comments.ejs中手动设置  
hc_github_config:
  type:
  owner:
  repo:
  client_id:
  client_secret:
  admin:
  vssue_theme_color:
hc_footer_info:[String]
    显示在页脚中的信息
    如:© YourName 2016-2018  
    支持html
hc_custom: [String]/false
    false: 无定制
    huno: huno风格(并不)
    其他: /themes/hunoc/source/css/custom_uno/ 中的css文件
hc_panel_addition: [String]/false
    false : 无
    [String] : 背景音乐或广告等等,支持HTML  
</pre>

### 背景图片

位于 source/images/background-cover.jpg  
或者修改图片URL。例如修改成CDN中的某个图片
    background: url("//img.alicdn.com/XXX") top left no-repeat #666666;
请参阅 [huno说明](https://github.com/letiantian/huno)  

### 归档页面

归档页面会显示分类、标签云以及基于日期的归档  
在hexo的配置文件或hunoc的配置文件_config.yml中:  

<pre>
hc_menu:
  首页: /#blog
  关于: /about
  归档: /archive
</pre>

创建新的page:
<pre>
    $ hexo new page archive
    $ cd source/archive
    $ index.md
</pre>

内容修改为:

<pre>
    ---
    title: 归档
    layout: page-archive
    ---
</pre>
hexo 默认有一个/archives，如果您认为归档页面的url（/archive）和这个冲突，可以选更加合适的名称  
请参阅 [huno说明](https://github.com/letiantian/huno)  

### 社交网站图标

<pre>
    social:
        github: tom
        500px: tom
</pre>
由于版权问题存疑,hunoc移除了China Social Icon
请参阅 [huno说明](https://github.com/letiantian/huno),_config.yml  

Foundation Icons v 3.0
 Made by ZURB 2013 [Official Site](http://zurb.com/playground/foundation-icon-fonts-3)
 MIT License

### 网站分析

    hc_site_analytics: (your analytics code from Google analysis,CNZZ etc.)

## 关于huno

作者: [letiantian](https://github.com/letiantian/)  
许可协议: [知识共享-署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)  
该主题基于[uno](https://github.com/daleanthony/uno/)  

## 关于uno

作者: [daleanthony](https://github.com/daleanthony/)  
许可协议: [知识共享-署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)  

## 兼容性

Hexo Theme Unit Test: 通过  
Hexo Theme Checklist: 符合:13 部分支持:2 不支持:2 未知:1  

在以下环境测试基本正常:

* hexo: 3.9
* node: 10~12
* 浏览器: Firefox/Chrome/Edge/IE 10,11
* 插件: hexo-all-minifier,hexo-deploy-git

## 建议

* 使用hexo-all-minifier插件
* 建议使用vssue,gitalk
* 注意,本主题暂不遵循语义版本,不能有规律地更新

## 其他引用项目

|项目|作者|许可协议|
|---|---|---|
|Vssue|[meteorlxy](https://github.com/meteorlxy)|MIT|
|[gitalk](https://github.com/gitalk/gitalk/)|[查看](https://github.com/gitalk/gitalk/graphs/contributors)|MIT|
|[gitment](https://github.com/imsun/gitment/)|[imsun](https://github.com/imsun/)|MIT|
|[JQueryRotate](http://jqueryrotate.com/)|Pawel "wilq32" Witkowski|MIT|
|[JQuery](https://jquery.com/)|JS Foundation and other contributors|jquery.org/license|

## 图片来源

感谢诸位!  

|图片|作者|许可协议|
|---|---|---|
|Red and blue sky – end of day|[Peter Janzen](https://cc0.photo/author/peter/)|[CC0公有领域(CC0 1.0 Universal Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/)|
|Picography lake view bridge|[Gratisography](https://gratisography.com/)|[CC0公有领域(CC0 1.0 Universal Public Domain Dedication)](https://creativecommons.org/publicdomain/zero/1.0/)|
