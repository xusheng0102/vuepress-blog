[![vuepress](https://img.shields.io/badge/vuepress-1.0.0--alpha.42-blue.svg)](https://v1.vuepress.vuejs.org/)
[![valine](https://img.shields.io/badge/valine-1.3.4-blue.svg)](https://valine.js.org/)
[![element-ui](https://img.shields.io/badge/element-2.6.1-blue.svg)](http://element-cn.eleme.io/)

## vuepress版本为1.x
## 运行项目

    yarn install //安装依赖
    yarn dev //运行

## 本地演示
> 如果看到下面这行即说明开发运行正常

    VuePress dev server listening at http://localhost:8080/

> 打开浏览器，输入localhost:8080即可访问

## demo
[demo](https://www.finen.top/)

## 开发

> 如果您想用该项目部署您自己的blog，请fork本项目，然后clone到您本地即可更改。如果您懂vue.js,那您可以自己开发一部分插件。

## 功能
- [x] Archives
- [ ] Tags Cloud
- [ ] Cate

## 评论功能

### 评论工具1 Valine.js
[Valine.js使用方法](https://valine.js.org/)

### 评论工具2 gittalk
[Gittalk](https://gitalk.github.io/)

### 评论工具3 gitment
[Gitment](https://imsun.github.io/gitment/)


    代码已经写好，在.vuepress目录下的enhanceApp.js中，依照网上配置可以很轻松使用Gitment或者Gittalk。
    Valine.js的某些bug确实有点烦恼，目前还在修缮中！



## 禁止评论
> 很多情况的页面都不想被评论，所以在每篇文档开头设置即可！如下：

    ---
    title: git 进阶操作命令
    comments: true or false
    ---
    true: 可以评论，false: 禁止评论

## 官网文档

[Vuepress文档](https://vuepress.docschina.org/)

## Valine.js食用方法
[Valine.js文档](https://valine.js.org/)

## 浏览器支持
Most browsers(Firefox,Chrome等)

## vuepress 0.14版本请参看readme0.x.md

## TODO

 1. 使用其他方法更新评论组件 或者使用其他较为好用的评论组件
 2. 添加categories and tag
 3. 跟换其他主题

## LiCENSE
MIT