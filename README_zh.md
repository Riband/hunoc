# hunoc

[English](./README.md)

## 项目状态

### 稳定版

[![GitHub release](https://img.shields.io/github/release/Riband/hunoc.svg?style=flat-square)](https://github.com/Riband/hunoc/releases/)
![GitHub Release Date](https://img.shields.io/github/release-date/Riband/hunoc.svg?style=flat-square)  

### 测试版

![GitHub (pre-)release](https://img.shields.io/github/release/Riband/hunoc/all.svg?style=flat-square)  
![GitHub (pre-)Release Date](https://img.shields.io/github/release-date-pre/Riband/hunoc.svg?style=flat-square)  
huno版本: commit 287f824

![GitHub last commit](https://img.shields.io/github/last-commit/Riband/hunoc.svg?style=flat-square)  

## 介绍

在用Hexo制作静态博客(CloudySummer Blog @Bitbucket)时,选择了Huno主题,为了满足一些需要,自己进行了一些修改,算是第一个正经项目吧.  
自娱自乐的Commit,Release,写更新日志<del>(明明一个注意到的也没有....)</del>,嘛,做人最重要的是开心.  

## 特性

### 在Huno的基础上

* 增加背景音乐选项
* 增加定制选项(进一步用CSS自定义)
* 更丰富的页脚自定义 (版权 版本)
* 使用半透明背景
* 更换字体
* 清理commit以节省空间
* 修正无评论功能时有多余白线
* 允许再导航按钮中使用HTML  
* 支持Gitment/Gitalk (请勿滥用!)

## 演示

做Demo属无事可<del>commit</del>做  
![hunoc Demo Img](https://riband.github.io/RiBase/hunoc-demo/demo.jpg)  

## 主题选项
[theme]: /themes/hunoc/_config.yml  
[config]: /_config.yml  
[post]: /source/_post/*.md  

    hc_post_comments: [String]/false
         false: 无评论功能  
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
    [theme]d

    hc_footer_info:[String]
          显示在页脚中
          [theme]

    hc_footer_info:[String]
        如:  
          © 2016-2018  
          CC-BY 4.0 International  
          [config|theme] [post(license_information instead)]

    hc_custom: [String]/false
        false: 无定制
        glass: 玻璃感  
        red_and_white: 红白
        grace: 雅
        (其他): /themes/hunoc/source/css/custom_uno/中的css文件
        [config|theme|post]

    hc_bgm: [String]/false
        false: 无背景音乐
        [String]: mp3文件地址(http(s)://**.mp3)  
        [config|theme|post]

    hc_iframe_bgm: [String]/false
        false: 无背景音乐
        [String]: HTML 代码
        [config|theme|post]

## hunoc主题

hunoc 是一个基于 [huno](https://github.com/letiantian/huno/) 的 Hexo 主题.  
本作品采用 [Mozilla 公共许可证 Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)进行许可.  

## 关于huno

Huno是为[Hexo](http://hexo.io/)编写的一个响应式的主题，该主题基于[Uno](https://github.com/daleanthony/uno/).  
作者: [letiantian](https://github.com/letiantian/)  
Huno采用 [知识共享-署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可.  
[![cc-by-nc-sa](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  

## 关于uno

作者: [daleanthony](https://github.com/daleanthony/)  
License: Creative Commons Attribution 4.0 International  
Uno采用 [知识共享-署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)进行许可.  
[![cc-by-nc-sa](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  

## 兼容性

在以下环境测试基本正常:

* hexo: 3.8.0
* node: 10.14.1
* Browsers: Firefox/Chrome/Edge/IE11
* Plugins: hexo-all-minifier,hexo-deploy

建议使用Gitalk
