# weChat-applet
区别
1，无BOM和DOM对象
2，a:APP全局应用对象函数
  b:getApp获取全局应用对象函数
  c:page页面对象函数
  d:getCurrentPages获取页面对象列表第一个是首页，最后一个是当前页面的对象
  e:wx提供核心微信api
3，符合commomJs组件规范 module.export = {getData:getData}  require("../../utils/index.js")
