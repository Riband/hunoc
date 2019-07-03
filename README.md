# hunoc

[中文](./README_zh.md)

## Introduction

hunoc is a hexo theme based on [huno](https://github.com/letiantian/huno/).  
License: [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)  
In order to meet some needs,I have made some changes on hunoc. It may be the first serious project for me.  
I like commiting,releasing,writing update log.Well,the most important thing is to be happy.  

## Project Status

This project is in FROZEN period

### Stable

[![GitHub release](https://img.shields.io/github/release/Riband/hunoc.svg?style=flat-square)](https://github.com/Riband/hunoc/releases/) ![GitHub Release Date](https://img.shields.io/github/release-date/Riband/hunoc.svg?style=flat-square)  

### Dev

![GitHub (pre-)release](https://img.shields.io/github/release/Riband/hunoc/all.svg?style=flat-square) ![GitHub (pre-)Release Date](https://img.shields.io/github/release-date-pre/Riband/hunoc.svg?style=flat-square) ![GitHub last commit](https://img.shields.io/github/last-commit/Riband/hunoc.svg?style=flat-square)  
huno version: Commit-2693076 (2019-01-12)

## Main Features

### Inheriting huno's features(With some modifications)

* A responsible theme
* [Mathjax](https://www.mathjax.org) Math formula support
* [Awesome_toc](https://github.com/letiantian/awesome-toc).Automaticly generate a index for your pages
* [GitHub Repo Widget](https://github.com/JoelSutherland/GitHub-jQuery-Repo-Widget) support
* Social icons
* Indepedent archive pages

### New

* The "hc_custom" option to custom hunoc with your own css
* Translucent looks
* Enable to use HTML Code in some options
* Support Vssue,Gitment,Gitalk , which are based on the issue system of the Github
* Better child path support.You only need change the config.root option
* More flexibile theme options,which can be used in many places

## Demo

[View](https://riband.github.io/hunoc-demo/)  

## How to use

### Method 1: Download and Unzip(Recommended)

1. Open the [latest stable release page](https://github.com/Riband/hunoc/releases/latest)
2. Download **Source code(zip)**
3. Unzip it to &lt;Your hexo path&gt;/themes/hunoc
4. Edit hexo's _config.yml
    <pre>theme: hunoc</pre>
5. If your'd like to config more about this theme,edit themes/hunoc/_config.yml  
  but you'd better copy the option to you hexo's _config.yml instead of hunoc-theme's

### Method 2: Git Clone

1. Start your shell/cmd and enter your hexo path
2. make sure your installed git,and run:  
    git clone git://github.com/someus/hunoc.git themes/hunoc
3. Edit hexo's _config.yml  
    theme: hunoc
4. If your'd like to config more about this theme,edit themes/hunoc/_config.yml,but you'd better copy the options to your hexo's config.yml instead of theme's

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
Or just paste it in the bottom of layout/_scripts/site-analytics.ejs

## About huno and uno

[huno](https://github.com/letiantian/huno) is a [Hexo](http://hexo.io/) theme，based on [uno](https://github.com/daleanthony/uno/)  
Author: [letiantian](https://github.com/letiantian/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

[uno](https://github.com/daleanthony/)  
Author: [daleanthony](https://github.com/daleanthony/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## Compatibility

Hexo Theme Unit Test: PASSED  
Hexo Theme Checklist: YES:13 PARTLY:2 NO:2 UNKNOWN:1  

It's generally tested on:  

* hexo: 3.9
* node: 10~12
* Browsers: Firefox/Chrome/Edge/IE 10 11
* Plugins: hexo-all-minifier,hexo-deploy-git

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
|[gitalk](https://github.com/gitalk/gitalk/)|booxood and [others](https://github.com/gitalk/gitalk/graphs/contributors)|MIT|
|[gitment](https://github.com/imsun/gitment/)|[imsun](https://github.com/imsun/)|MIT|
|[JQueryRotate](http://jqueryrotate.com/)|wilq32 and [others](https://github.com/wilq32/jqueryrotate/graphs/contributors)|MIT|
|[JQuery](https://jquery.com/)|JS Foundation and other contributors|jquery.org/license|

## Picture Authors

Thank these generous guys!  

|Picture|Author|License|
|---|---|---|
|Red and blue sky – end of day|[Peter Janzen](https://cc0.photo/author/peter/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|
|Picography lake view bridge|[Gratisography](https://gratisography.com/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|
