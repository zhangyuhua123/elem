饿了吗
首先搭建项目环境  vue-cli,初始化项目。。。

-build
-config
-node_modules	// node包
-src			// 项目代码所在文件夹		
-.babelrc
-.editorconfig
-.eslintignore
-.eslintrc.js
-.gitignore
-index.html
-package.json
-README.md

Vuex 安装

vue2 + vuex2 + vue-router2 + vue-swipe + vue-cli

运用了状态管理
在全局状态下安装了store,state是态数据，触发action，mutations会去改变state的值，getters对外提拱state的值

由于数据是假数据，要产生真数据的效果，我用setTimeout模拟下数据的加载，展示加载动画，computed中使用mapGetters来得到state中的数

组件分为首页，商品详情页，搜索页，登录页，我的个人中心页，订单页和大组件被拆散的小组件（一个商家组件，尾部导航栏组件，评分组件，登录的头部组件）

商品首页中，商家简介中15个商家是一个分界点，超出15个加载

在商家管理界面：
通过两个选项卡轮流切换显示商品还是评级

商品这个界面我分为左右两部分，通过左列表的切换来读取右列表当前的显示是哪个商品（数据都是伪造的）
商品界面中还有一个结算的弹出框，购物车 data中定义一个购物车对象{ }，添加某样商品时，已存在就+1，
不存在则添加属性，每次添加计算总价等相关数据。这边运用到了运动函数里讲的一个抛球效果，

在登录界面中,登录的密码和账号都是admin



SVG是矢量图形文件，可以随意改变大小，而不影响图标质量。
　　可以用CSS样式来自由定义图标颜色，比如颜色/尺寸等效果。
　　所有的SVG可以全部在一个文件中，节省HTTP请求 。
　　使用SMIL、CSS或者是javascript可以制作充满灵性的交互动画效果。
　　由于SVG也是一种XML节点的文件，所以可以使用gzip的方式把文件压缩到很小
