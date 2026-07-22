---
title: hexo帮助
date: 2025-06-23 18:07:01
layout: hexo帮助
---
# 教程
在官网下载安装 node.js

安装 hexo-cli  
`npm install -g hexo-cli`

进入工作目录  
`cd gameswebsite`

生成网站  
`hexo g`

部署  
`hexo d`

一键生成与部署  
`hexo g -d`

# 更新hexo版本

全局升级hexo-cli
`npm i hexo-cli -g`

再次查看版本，看hexo-cli是否升级成功
`hexo version`

安装npm-check，若已安装可以跳过
`npm install -g npm-check`

检查系统插件是否需要升级
`npm-check`

安装npm-upgrade，若已安装可以跳过
`npm install -g npm-upgrade`

更新package.json
`npm-upgrade`

更新全局插件
`npm update -g`

更新系统插件
`npm update --save`

再次查看版本，判断是否升级成功
`hexo version`
