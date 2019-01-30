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

在用Hexo制作静态博客,选择了Huno主题,为了满足一些需要,自己进行了一些修改,算是第一个正经项目吧.  
自娱自乐的Commit,Release,写更新日志<del>(明明一个注意到的也没有....)</del>,嘛,做人最重要的是开心.  

## 特性

### 在Huno的基础上

* 增加定制选项(进一步用CSS自定义)
* 更丰富的页脚自定义
* 使用半透明背景
* 更换字体
* 清理commit以节省空间
* 修正无评论功能时有多余白线
* 允许在导航按钮中使用HTML  
* 支持Gitment/Gitalk
* 更好的子目录支持(仅需修改root)
* 移除了动画
* 等等

## 演示

做Demo属无事可<del>commit</del>做  
[查看](https://riband.github.io/hunoc-demo/)
![hunoc Demo Img](https://riband.github.io/RiBase/hunoc-demo/demo.jpg)  

## 主题选项

所有的选项都可以在/theme/_config.yml,/_config.yml,/source/*.md中使用,有特殊注明的除外  
请以/theme/_config.yml中的说明为准  

    hc_post_comments: [String]/false
         false: 无评论功能  
         gitment: gitment
         gitalk: gitalk
         manual (or other string): you will config manually in comments.ejs  

    hc_github_config(you must set hc_post_comments: gitment)
      owner:
      repo:
      client_id:
      client_secret:
      admin:

    hc_footer_info:[String]
          显示在页脚中

    hc_footer_info:[String]
        如:© 2016-2018  
          CC-BY 4.0 International  
          支持html

    hc_custom: [String]/false
        false: 无定制
        huno: huno风格
        (其他): /themes/hunoc/source/css/custom_uno/中的css文件

## 关于hunoc

hunoc 是一个基于[huno](https://github.com/letiantian/huno/)的一个响应式的Hexo主题.  
许可协议:[Mozilla 公共许可证 Version 2.0](https://www.mozilla.org/en-US/MPL/2.0/)  

## 关于huno

作者: [letiantian](https://github.com/letiantian/)  
许可协议: [知识共享-署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)  
该主题基于[uno](https://github.com/daleanthony/uno/)  

## 关于uno

作者: [daleanthony](https://github.com/daleanthony/)  
许可协议: [知识共享-署名 4.0 国际许可协议](http://creativecommons.org/licenses/by/4.0/)  

## 兼容性

在以下环境测试基本正常:

* hexo: 3.8.0
* node: 10.15.1 / 11.8.0
* 浏览器: Firefox/Chrome/Edge/IE11
* 插件: hexo-all-minifier,hexo-deploy
* 建议使用vssue,gitalk

## 建议

* 使用hexo-all-minifier插件
* 注意,本主题暂不遵循语义版本,不能有规律地更新

## 图片来源

感谢诸位!  

|图片|作者|许可协议|
|---|---|---|
|Red and blue sky – end of day|[Peter Janzen](https://cc0.photo/author/peter/)|[CC0共有领域](https://creativecommons.org/publicdomain/zero/1.0/)|
|Picography lake view bridge|[Gratisography](https://gratisography.com/)|[CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/)|