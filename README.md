
vue2 + vuex2 + vue-router2 + vue-swipe + vue-cli

首先需要安装vue-cli，vue-cli是一个快速搭建vue项目的工具

// 安装 vue-cli
npm install -g vue-cli

// 初始化一个项目
vue init webpack my-project

// 然后一路回车，记得勾选上vue-router
// 输入以下命令，等待浏览器打开
cd my-project
npm install
npm run dev

npm install vuex -S

######在src目录下创建store.js
```
// store.js
import Vue from 'vue'
import Vuex from 'vuex'
Vue.use(Vuex) // 要记得use一下哦

