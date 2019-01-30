# hunoc

[中文](./README_zh.md)

## Project Status

### Stable

[![GitHub release](https://img.shields.io/github/release/Riband/hunoc.svg?style=flat-square)](https://github.com/Riband/hunoc/releases/)  
![GitHub Release Date](https://img.shields.io/github/release-date/Riband/hunoc.svg?style=flat-square)  

### Dev

![GitHub (pre-)release](https://img.shields.io/github/release/Riband/hunoc/all.svg?style=flat-square)  
![GitHub (pre-)Release Date](https://img.shields.io/github/release-date-pre/Riband/hunoc.svg?style=flat-square)  
hunoc version: commit 287f824

![GitHub last commit](https://img.shields.io/github/last-commit/Riband/hunoc.svg?style=flat-square)  

## Introduction

When using hexo to generate my static blog,I chose the hunoc theme.In order to meet some needs,I have made some changes on hunoc. It may be the first serious project for me.  
I amuse myself by commiting,releasing,writing update log.<del>(obviously no one notice it)</del>Well, the most important thing is to be happy.  

## Features

### Comparing to hunoc

* Add Custom option (Custom your theme with your own css)
* Use Translucent Background
* Change Fonts
* Clean commits of huno to save some space
* Fix : there's extra line when comment is disabled
* Enable use HTML Code in hc_menu:  
* Gitment/Gitalk Supported
* Better subpath support(Need only change root)
* Remove animate
* Etc.

## Demo

![hunoc Demo Img](https://riband.github.io/RiBase/hunoc-demo/demo.jpg)  

## Theme Options

Every option is available in these files excluding ones with explanation.And you can use html in most of them.  
Please read the instruction in /_config.yml for detailed and correct infomation.

* /themes/hunoc/_config.yml  
* /_config.yml  
* /source/_post/*.md  

    hc_post_comments: [String]/false
         false: no comments  
         gitment: use gitment(must cofig the hc_github_config)
         gitalk: use gitalk(must cofig the hc_github_config)
         manual (or other string): you will config manually in comments.ejs  

    hc_github_config: (you must set hc_post_comments: gitment/gittalk)
        owner:
        repo:
        client_id:
        client_secret:
        admin:

    hc_footer_info:[String]
          Printed on the footer of a page
          only theme/_config.yml

    hc_custom: [String]/false
         false: None custom
        (other): file name in /themes/hunoc/source/css/custom_uno/  

    hc_panel_addition: [String]/false
        false : No
        [String] : HTML code for your bgm or ads  

## About hunoc

hunoc is a hexo theme based on [hunoc](https://github.com/letiantian/hunoc/).
License: [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)  

## About huno

huno is a [Hexo](http://hexo.io/) theme，based on [uno](https://github.com/daleanthony/uno/).  
Author: [letiantian](https://github.com/letiantian/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## About uno

Author: [daleanthony](https://github.com/daleanthony/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## About gitalk

Author: booxood,mamboer,devrsi0n,meteorlxy,CoderMing,cometeme,xnng ......  
[View all contributors](https://github.com/gitalk/gitalk/graphs/contributors)  
Sites: [gitalk](https://github.com/gitalk/gitalk/)  
License: MIT

## Compatibility

It's generally tested on:

* hexo: 3.8.0
* node: 10.15.1 / 11.8.0
* Browsers: Firefox/Chrome/Edge/IE 11
* Plugins: hexo-all-minifier,hexo-deploy
* vssue and gitalk is recommended.

## Suggestions

* Use hexo-all-minifier(Plugin)
* If you want to keep up-to-date,you need to know:
    This theme DO NOT obey Semantic Versioning now(AT LEAST before 1.0.0)
    This theme DO NOT update regularly

## Picture Authors

Thank these generous guys!  

|Picture|Author|License|
|---|---|---|
|Red and blue sky – end of day|[Peter Janzen](https://cc0.photo/author/peter/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|
|Picography lake view bridge|[Gratisography](https://gratisography.com/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|

Some authors are still being searched...