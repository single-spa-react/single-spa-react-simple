<h1 align="center">single-spa-react-simple</h1>

<div align="center">

single-spa-react-simple 非常简单基础的微前端demo 🚀🚀🚀,适合没有相关开发经验或者有非常丰富经验需要定制开发的同学！没有任何状态管理库！

[![Documentation](https://img.shields.io/badge/documentation-yes-brightgreen.svg)](https://github.com/single-spa-react/single-spa-react-simple#readme) [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/single-spa-react/single-spa-react-simple/graphs/commit-activity) [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/single-spa-react/single-spa-react-simple/blob/master/LICENSE)

</div>

## ⌨️ 本地开发

```bash
$ git clone git@github.com:single-spa-react/single-spa-react-simple.git
$ cd single-spa-react-simple
$ npm install
$ npm start
```

注意⚠️： 

react-router-dom v6版本的使用方式有较大改动：

Switch --> Routes

Component ---> element

```js
<Routes>
   {routes.map((route, index) => (
   <Route key={index}
      routeKey={route.key}
      exact={route.exact}
      path={route.path}
      element={route.element} />
   ))}
</Routes>
```

打开浏览器访问 http://127.0.0.1:8000/project1/。

## 相关资料： 
1，项目依赖包梳理：https://segmentfault.com/a/1190000019006667

## 相关推广

1. https://github.com/xlei1123/daymanage
   > 这是一个使用 umi 开发的项目，想学习 umi 的新手可以学习一下
2. https://github.com/xlei1123/dtext
   > 前端文案默认值处理利器，统一定制修改，同时支持使用时特殊指定




