## 目前页面性能问题（排名不分先后）
* 1.静态资源http请求数过多。

    模块和组件的js，css分开请求，个数较多

    页面中的一些icon没有使用背景图片，或是使用背景图片没有做css sprite

* 2.页面中图片体积过大，压缩不彻底

    主要体现在banner，活动图片；优化方法见[优化图片](./gold/home.md)

* 3.页面中图片未做lazyload

    如banner，轮播图，商品图片等。

* 4.一些统计代码没有做压缩

* 5.用户中心mobile没有做合并打包

