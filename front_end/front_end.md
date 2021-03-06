---
title: 前端汇总
date: 2018-02-02 16:14:09
categories:
  - 前端
tags:
  - 前端
abbrlink: 5fbe9a01866e41f3
---

# 编程语言

## html

## css

input 美化：
* [css input type=file 样式美化，input上传按钮美化](http://www.haorooms.com/post/css_input_uploadmh)

css 居中对齐
* [6 Methods For Vertical Centering With CSS](http://vanseodesign.com/css/vertical-centering/)
* [CSS Layout - Horizontal & Vertical Align](https://www.w3schools.com/csS/css_align.asp)
* [Centering in CSS: A Complete Guide](https://css-tricks.com/centering-css-complete-guide/)

css 可用性查询：
* [css 可用性查询](http://caniuse.com/)

## javascript

浏览器api：
* [Web API 接口](https://developer.mozilla.org/zh-CN/docs/Web/API)
* [Window](https://developer.mozilla.org/en-US/docs/Web/API/Window)

事件冒泡机制：
* [javascript 事件机制－冒泡与捕获](http://www.cnblogs.com/hustskyking/p/problem-javascript-event.html)

input 加载本地文件：
* [Reading files in JavaScript using the File APIs](https://www.html5rocks.com/en/tutorials/file/dndfiles/)
* [Using files from web applications](https://developer.mozilla.org/en-US/docs/Using_files_from_web_applications)

# 认证

* [Auth-boss](https://github.com/teesloane/Auth-Boss)

常见的认证方法：
* HTTP Basic Authentication
* Session based Authentication
* Token based Authentication
* JWT
* OAuth
* OpenId

# 文件上传

文件上传主要使用以下两种方法：
1. html 的 form input 元素
2. XMLHttpRequest 里的 FormData

* [非常有用的文件上传脚本收集](https://www.qianduan.net/very-useful-collection-of-the-file-upload-script/)
* [文件各种上传离不开的表单](http://www.ibloger.net/article/2556.html)
* [文件上传那些事儿](https://juejin.im/entry/590ad4682f301e00582a78b5)
* [前端文件上传基础](http://www.jianshu.com/p/374e9b9d1fb1)

# web storage

* [Web Storage API](https://developer.mozilla.org/zh-CN/docs/Web/API/Web_Storage_API)
* [详说 Cookie, LocalStorage 与 SessionStorage](http://jerryzou.com/posts/cookie-and-web-storage/)
* [Cookie/Session机制详解](http://blog.csdn.net/fangaoxin/article/details/6952954)
* [Web如何使用cookie，MVC如何使用cookie](http://www.cnblogs.com/denglj/p/4120495.html)

# 日期与时间格式

* [Date and Time Formats](https://www.w3.org/TR/NOTE-datetime)

# 字体图标

* [Font Awesome](http://www.fontawesome.com.cn/)

# ajax

* AJAX = Asynchronous JavaScript and XML（异步的 JavaScript 和 XML）。
* AJAX 不是新的编程语言，而是浏览器的一个方法。
* AJAX 最大的优点是在不重新加载整个页面的情况下，可以与服务器交换数据并更新部分网页内容。
* 尽管X在Ajax中代表XML, 但由于JSON的许多优势，比如更加轻量以及作为Javascript的一部分，目前JSON的使用比XML更加普遍。JSON和XML都被用于在Ajax模型中打包信息。
* [Ajax](https://developer.mozilla.org/zh-CN/docs/Web/Guide/AJAX)

# angularjs

factory,service与provider的区别：
* [AngularJS：factory，service与provider的区别](https://segmentfault.com/a/1190000004602085)
* [Angularjs 中的 provider, factory 和 service](http://zhex.me/blog/2013/08/03/provider-factory-and-service-in-angularjs/)
* [伤不起的providers](http://hellobug.github.io/blog/angularjs-providers/)

form：
* [form 进阶](https://github.com/tiw/angularjs-tutorial/blob/master/ng-form2.markdown)
* [angularjs form简单入门](http://www.angularjs.cn/A08j)

插件：
* [angular-file-upload](https://github.com/nervgh/angular-file-upload)
* [UI-Router for AngularJS (1.x)](https://ui-router.github.io/ng1/)

调试：
* [在控制台中调试 AngularJS 应用（译/改）](https://lyfeyaj.com/2015/01/07/debugging-angularjs-apps-from-the-console/)

常见问题：
* angular.element 与 jQuery的关系:  If jQuery is available, angular.element is an alias for the jQuery function. If jQuery is not available, angular.element delegates to AngularJS's built-in subset of jQuery, called "jQuery lite" or jqLite.
* 如何复写ngClick：[AngularJS - how to override directive ngClick](https://stackoverflow.com/questions/18421732/angularjs-how-to-override-directive-ngclick)

# 浏览器

* [浏览器渲染页面过程](http://www.cnblogs.com/chenlogin/p/5221562.html)

# RESTful api

REST的核心原则是将你的API拆分为逻辑上的资源。这些资源通过http被操作（GET,POST,PUT,DELETE）。

# 自动测试

* [karma](https://karma-runner.github.io/2.0/index.html) : 为测试代码提供真实的浏览器环境
* [jasmine](https://jasmine.github.io/) : javascript测试框架


# 辅助工具

* postman: http 工具
* [name the color](http://chir.ag/projects/name-that-color/#6195ED)
* [网页栅格化工具： GridGuide](http://www.shejidaren.com/gridguide.html)

# MVC

MVC本来是存在于Desktop程序中的，M是指数据模型，V是指用户界面，C则是控制器。使用MVC是将M和V的实现代码分离，从而使同一个程序可以使用不同的表现形式。

* [Understanding Model-View-Controller](https://blog.codinghorror.com/understanding-model-view-controller/)
* [Model–view–controller](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)

# 跨浏览器测试

# 布局

* [如何搭建Web端布局框架？来看滴滴设计团队的超全经验总结！](https://www.uisdc.com/web-layout-frame)

# 开发工具

* [响应式网站设计工具](http://www.coolsite360.com/)
* [飞冰-海量可复用物料，配套桌面工具极速构建前端应用](https://alibaba.github.io/ice/)
* [Froont - web design tool](http://froont.com/)

# 响应式

* [picturefill - A RESPONSIVE IMAGE POLYFILL](https://scottjehl.github.io/picturefill/)
* [Web性能优化：图片优化](http://www.cnblogs.com/wizcabbit/p/web-image-optimization.html)
* [实战响应式图片](http://efe.baidu.com/blog/responsive-images-in-practice/)
* [响应式图片 - 学习 Web 开发 | MDN](https://developer.mozilla.org/zh-CN/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

# 移动端开发

* [移动端前端开发调试](http://yujiangshui.com/multidevice-frontend-debug/)

# 网站收集

**漂亮的单页应用**

* [ejs](http://ejs.co)

# 跨域

https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Access_control_CORS

# 模板引擎


* [ART-TEMPLATE](http://aui.github.io/art-template/zh-cn/)
* [layui](https://www.layui.com/doc/)

* [mustache.js](https://github.com/janl/mustache.js/)

轻量度：tpl.js、T.js
认知度：arttemplate、mustache.js、doT.js、handlebars.js、pug
DOM-tree-based：domTemplate、transparency、plates
VDOM-based：htmltemplate-vdom、virtual-stache、html-patcher
流行框架：Vue.js、ReactJS、riot
Real-DOM：PowJS
