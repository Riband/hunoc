# hunoc

[中文](./README_zh.md)

## Project Status

### Stable

[![GitHub release](https://img.shields.io/github/release/Riband/hunoc.svg?style=flat-square)](https://github.com/Riband/hunoc/releases/)  
![GitHub Release Date](https://img.shields.io/github/release-date/Riband/hunoc.svg?style=flat-square)  

### Dev

![GitHub (pre-)release](https://img.shields.io/github/release/Riband/hunoc/all.svg?style=flat-square)  
![GitHub (pre-)Release Date](https://img.shields.io/github/release-date-pre/Riband/hunoc.svg?style=flat-square)  
huno version: commit 287f824

![GitHub last commit](https://img.shields.io/github/last-commit/Riband/hunoc.svg?style=flat-square)  

## Introduction

this Customed Huno is mainly used for my blog.**Other people are NOT advised to use this theme**,if you want to use a nice and stable hexo theme,see: [huno](https://github.com/letiantian/huno/).  
When using Hexo to generate my static blog,I chose the Huno theme.In order to meet some needs, I have made some changes on Huno. It may be the first serious project for me.  
I amuse myself by commiting,releasing,writing update log.<del>(obviously no one notice it)</del>Well, the most important thing is to be happy.  

## Features

### Comparing to huno

* Add background music option
* Add Custom option (Custom your theme with your own css)
* Use Translucent Background
* Change Fonts
* Clean commits of huno to save some space
* Fix : there's extra line when comment is disabled
* Enable use HTML Code in menu:  
* Gitment/Gitalk Supported
* Better subpath support(Need only change root)

## Demo

![hunoc Demo Img](https://riband.github.io/RiBase/hunoc-demo/demo.jpg)  

## Theme Options
[theme]: /themes/hunoc/_config.yml  
[config]: /_config.yml  
[post]: /source/_post/*.md  

    hc_post_comments: [String]/false
         false: no comments  
         gitment: gitment
         gitalk: gitalk
         manual (or other string): you will config manually in comments.ejs  
         [config|theme|post]

    hc_github_config(you must set hc_post_comments: gitment)
    * owner:
    * repo:
    * client_id:
    * client_secret:
    * admin:
    [theme]

    hc_footer_info:[String]
          Printed on the footer of a page
          [theme]

    hc_footer_info:[String]
        Such as:  
          © 2016-2018  
          CC-BY 4.0 International  
          [config|theme] [post(license_information instead)]

    hc_custom: [String]/false
         false: None custom
         glass: glass feeling
         red_and_white: red_and_white
         grace
        (other): file name in /themes/hunoc/source/css/custom_uno/
        [config|theme|post]  

    hc_pane l_addition: [String]/false
        false : No
        [String] : HTML code for your bgm or ads  
        [config|theme|post]

## About hunoc

hunoc is based on [Huno](https://github.com/letiantian/huno/).

this Customed Huno is mainly used for my blog.**Other people are NOT advised to use this theme</b>,if you want to use a nice hexo theme,see: [Huno](https://github.com/letiantian/huno/).
License: [Mozilla Public License Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)  

## About Huno

Huno is a [Hexo](http://hexo.io/) theme，based on [Uno](https://github.com/daleanthony/uno/).  
Author: [letiantian](https://github.com/letiantian/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## About Uno

Author: [daleanthony](https://github.com/daleanthony/)  
License: [Creative Commons Attribution 4.0 International](http://creativecommons.org/licenses/by/4.0/)  

## Compatibility

It's generally tested on:

* hexo: 3.8.0
* node: 10.14.1
* Browsers: Firefox/Chrome/Edge/IE 11
* Plugins: hexo-all-minifier,hexo-deploy

Gitalk is recommended.

## Updates For This Version

* link Gitment/Gitalk js properly
* Test IE11
* Rename the Project
* Make gitment/gitalk available in config/theme/post
* Make menu to hc_menu,available in config/theme/post

---

* remove hc_bgm , please use hc_panel_addition
* better support for subpath website

## Memo

* Add author avatar and sign
