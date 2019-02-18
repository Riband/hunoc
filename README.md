# hunoc

[中文](./README_zh.md)

## Introduction

hunoc is a hexo theme based on [huno](https://github.com/letiantian/hunoc/).  
License: [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)  
In order to meet some needs,I have made some changes on hunoc. It may be the first serious project for me.  
I like commiting,releasing,writing update log.Well,the most important thing is to be happy.  

## Project Status

**This Project is Frozen**

### Stable

[![GitHub release](https://img.shields.io/github/release/Riband/hunoc.svg?style=flat-square)](https://github.com/Riband/hunoc/releases/) ![GitHub Release Date](https://img.shields.io/github/release-date/Riband/hunoc.svg?style=flat-square)  

### Dev

![GitHub (pre-)release](https://img.shields.io/github/release/Riband/hunoc/all.svg?style=flat-square) ![GitHub (pre-)Release Date](https://img.shields.io/github/release-date-pre/Riband/hunoc.svg?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/Riband/hunoc.svg?style=flat-square)  
huno version: commit 287f824  

## Features

* Add Custom option (Custom your theme with your own css)
* Use Translucent Background
* Clean commits of huno to save some space
* Enable use HTML Code in hc_menu:  
* SupportVssue/Gitment/Gitalk comment
* Better subpath(child path) support(only need change root:)
* Remove animate
* Etc.

## Demo

[View](https://riband.github.io/hunoc-demo/)  
[![hunoc Demo Img](https://riband.github.io/RiBase/hunoc-demo/demo.jpg)](https://riband.github.io/hunoc-demo/)  

## How to use

### Method 1: Download and Unzip(Recommend)

1. Open the release page [https://github.com/Riband/hunoc/releases/](https://github.com/Riband/hunoc/releases/)
2. Download **Source code(zip)**
3. Unzip it to  &lt;Your hexo path&gt;/themes/hunoc
4. Edit hexo's _config.yml  
    theme: hunoc
5. If your'd like to config more about this theme,edit themes/hunoc/_config.yml,but you'd better copy the option to you hexo's _config.yml instead of theme's

### Method 2: Git Clone

1. Start your shell/cmd and enter your hexo path
2. make sure your installed git,and:  
    git clone git://github.com/someus/hunoc.git themes/hunoc
3. Edit hexo's _config.yml  
    theme: hunoc
4. If your'd like to config more about this theme,edit themes/hunoc/_config.yml,but you'd better copy the option to you hexo's config.yml instead of theme's

## Theme Options

Every option is available in these files excluding ones with explanation.And you can use html in most of them.  
Please read the instruction in /_config.yml for detailed and correct infomation.

* /themes/hunoc/_config.yml
* /_config.yml
* /source/_post/*.md

<pre>
hc_post_comments: [String]/false
    false: no comments  
    gitment: use gitment(must complete the hc_github_config list)
    gitalk: use gitalk(must complete the hc_github_config list)
    vssue: use vssue(must complete the hc_github_config list)
    manual: you will config manually in comments.ejs  
hc_github_config:
    type:
    owner:
    repo:
    client_id:
    client_secret:
    admin:
    vssue_theme_color:
hc_footer_info:[String]
      Information printed on the footer of a page
      only available in themes/_config.yml
hc_custom: [String]/false
    false: None custom
    huno: Original huno style(not very original)
    (others): file name in /themes/hunoc/source/css/custom_uno/  
hc_panel_addition: [String]/false
    false : No
    [String] : HTML code for your bgm or ads  
</pre>

### Background picture

Just put your picture as source/images/background-cover.jpg  
If you want to use a picture in CDN,please modify source/css/uno.css  
For more infomation,read [huno readme](https://github.com/letiantian/huno)  

### Archive

1. Execute:  
    hexo new page archive

2. Edit source/archive/index.md  

<pre>
    ---
    title: Archive
    layout: page-archive
    ---
</pre>
For more infomation,read [huno readme](https://github.com/letiantian/huno)  

### Social Icon

For example:
<pre>
social:
    github: YourName
    500px: YourName
</pre>
Do not need to edit social.yml  
For more infomation,read _config.yml  

Foundation Icons v 3.0  
    Author: ZURB 2013  
    Official Site: [http://zurb.com/playground/foundation-icon-fonts-3](http://zurb.com/playground/foundation-icon-fonts-3)  
    License: MIT  

### Site analytics

    hc_site_analytics: (your analytics code from Google analysis,CNZZ etc.)
Or just paste it in layout/_scripts/site-analytics.ejs

## About huno

[huno](https://github.com/letiantian/huno) is a [Hexo](http://hexo.io/) theme，based on [uno](https://github.com/daleanthony/uno/)  
Author: [letiantian](https://github.com/letiantian/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## About uno

[uno](https://github.com/daleanthony/)  
Author: [daleanthony](https://github.com/daleanthony/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## Compatibility

hexo-theme-unit-test: PASSED

It's generally tested on:

* hexo: 3.8.0
* node: 10.15.1 / 11.10.0
* Browsers: Firefox/Chrome/Edge/IE 11/IE 10
* Plugins: hexo-all-minifier,hexo-deploy

## Suggestions

* Use hexo-all-minifier(Plugin)
* If you want to keep up-to-date,you need to know:
    This theme DO NOT obey Semantic Versioning now
    This theme DO NOT update regularly
* Vssue and gitalk are recommended.

## Other cited projects

|Project|Author|License|
|---|---|---|
|[Vssue](https://vssue.js.org/)|[meteorlxy](https://github.com/meteorlxy)|MIT|
|[gitalk](https://github.com/gitalk/gitalk/)|[View](https://github.com/gitalk/gitalk/graphs/contributors)|MIT|
|[gitment](https://github.com/imsun/gitment/)|[imsun](https://github.com/imsun/)|MIT|
|[JQueryRotate](http://jqueryrotate.com/)|Pawel "wilq32" Witkowski|MIT|
|[JQuery](https://jquery.com/)|JS Foundation and other contributors|jquery.org/license|

## Picture Authors

Thank these generous guys!  

|Picture|Author|License|
|---|---|---|
|Red and blue sky – end of day|[Peter Janzen](https://cc0.photo/author/peter/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|
|Picography lake view bridge|[Gratisography](https://gratisography.com/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|