# koa2 demo

> 引自：https://chenshenhai.github.io/koa2-note/

#  对应目录说明
## index.js    
快速开始demo

## index2.js
koa2 原生路由实现

## index3.js
koa2 定制化路由

## router-middleware.js
koa-router 中间件

    npm install --save koa-router@7

## get.js
GET请求数据获取

## post.js
POST请求数据获取

## post-mideleware.js
koa-bodyparser中间件
对于POST请求的处理，koa-bodyparser中间件可以把koa2上下文的formData数据解析到ctx.request.body中

    npm install --save koa-bodyparser@3

## 4.0
index.js 原生koa2实现静态资源服务器

koa-static.js 使用中间件koa-static

## 5.0
index.js  koa2使用cookie
index2.js koa2实现session

## 6.0
index.js 使用模板引擎

    # 安装koa模板使用中间件
    npm install --save koa-views

    # 安装ejs模板引擎
    npm install --save ejs


