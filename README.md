# vue-bookstore用户端

1.这是一个使用Vue.js开发的网上书店，设计成移动端的形式。主要使用VueX,Vue-Router等。
2.ui框架主要用了适合制作商城系统的vant-Ui和Mint-Ui。
3.首页的修改主题通过使用vcolorpicker插件实现，通过将选中的颜色保存到VueX里，通过computed实现主题颜色切换。
4.Vue.js一经刷新,VueX里的数据就会被清空，这里使用了vuex-persist插件，使数据持久化存储。
5.分类页面的左右联动通过通过better-Scroll实现。
6.与客服聊天，这里使用了WebSocket来实现实时聊天。

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

<p>
<img src="http://pqdg4ilq2.bkt.clouddn.com/image/bookstore/1.png" >
</p>
