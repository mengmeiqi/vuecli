# vuecli
    网址:https://cn.vuejs.org/v2/guide/installation.html
        https://github.com/vuejs/vue-cli
    1)安装vue-cli脚手架构建工具，npm install vue-cli -g， 安装 完成之后输入vue-V(注意这里是大写的“V”) 如果出现相应的版本号，则说明安装成功
    2)在硬盘上找一个文件夹放工程用的,cd 目录路径
    3)安装vue脚手架输入:vue init webpack projectname ,注意这里的“projectname” 是项目的名称可以说是随便的起名， 但是需要主要的是“不能用中文”
    4)cd 命令进入创建的工程目录，首先cd projectname(这里是自己建工程的名字); 
    5)安装项目依赖:npm install(时间比较长)
    6)启动项目，输入:npm run dev
    [HMR]Waiting for update signal from WDS...
    WDS:webpack-dev-server
    HMR:Hot Module Replacement
# vue-router
    vue-router是Vue.js官方的路由插件，它和vue.js是深度集成的，适合用于构建单页面应用。vue的单页面应用是基于路由和组件的，路由用于设定访问路径，并将路径和组件映射起来。传统的页面应用，是用一些超链接来实现页面切换和跳转的。vue-router单页面应用中，则是路径之间的切换，也就是组件的切换。 
# 我们是如何看到首页的？
    整体只有一个HTML文件，有一个挂载文件叫做app，一个入口文件main.js,通过router.js实现一个映射关系，我们需要自己定义组件，定义在components里面，文件以.vue结尾，包括三部分<template>,<script>,<style>