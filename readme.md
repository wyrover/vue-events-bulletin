## Vue Events Bulletin Board

This is the code for the Vue.js [tutorial on Scotch.io](https://scotch.io). In the tutorial we build a events bulletin board application and cover the basics of [Vue](http://vuejs.org/).

用来做一些简单的例子测试，用 express 做 RESTful Api。

最新的 vue.js 框架已经可以使用 `.vue` 的打包组件，要使用这种格式必须提供一个 webpack 或者 browserfiy 的打包器，如果只是测试一些简单的例子，可以直接在 html 引用。


## Installation


```
cnpm install bootstrap ejs express morgan vue vue-resource --save
cnpm install body-parser errorhandler method-override morgan --save-dev
```


1. Run `npm install`.
2. Run `node server.js`.
3. Visit [http://localhost:8080](http://localhost:8080).

## RESTful API (contributed by Jason Lam)

1. **Use Node.js & Express for backend server and router.**
2. **RESTful requests towards the server to simulate CRUD on *events* model, instead of local hardcoded ones.**
3. Translated into Traditional Chinese.
