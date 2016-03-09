# React生态清单


## Basic
1. [react官网文档](http://facebook.github.io/react/docs/getting-started.html)
1. [react社区](https://discuss.reactjs.org/)
1. [新手没有配置react环境,可以试试这个playground](https://jsfiddle.net/reactjs/69z2wepo/)

## 教程推荐
1. [react-primer-draft](https://github.com/mikechau/react-primer-draft#proptypes)
1. [react同构渲染教程](http://eflorenzano.com/blog/2014/04/09/react-part-1-getting-started/)
1. [react服务端react渲染项目示例,服务端用的是node](http://eflorenzano.com/blog/2014/04/09/react-part-1-getting-started/)
1. [react服务端渲染教程](http://yanns.github.io/blog/2014/03/15/server-side-rendering-for-javascript-reactjs-framework/)
1. [react+php服务端渲染](http://www.phpied.com/server-side-react-with-php/)
1. [react+php同构渲染](http://ericescalante.com/2015/06/07/isomorphic/)
1. [react+webpack](http://survivejs.com/webpack/introduction/)

## react脚手架
1. [babel](https://babeljs.io/): es6编译器
1. [react-router](https://github.com/reactjs/react-router): react路由
1. [redux](https://github.com/reactjs/redux): react状态管理
1. [webpack](https://webpack.github.io/): 构建工具

## react工程模板
1. [react-starter-kit](https://github.com/kriasoft/react-starter-kit)
1. [react-redux-universal-hot-example](https://github.com/erikras/react-redux-universal-hot-example)
1. [react-transform-boilerplate](https://github.com/gaearon/react-transform-boilerplate)
    
    react-transform-boilerplate是一个搭建好的 Webpack + React 的样板项目。我们可以基于它来做我们后续的开发。
    项目中自带的功能有:
* react 模块热加载功能 ( HMR )
* 直接在页面中报错功能 ( catches errors inside render() )
* ES6 支持 (通过 Babel6 )

## react组件搜索
1. [react+react-native组件搜索](https://react.parts/)
1. [React Component List](http://dvemac.github.io/react-component-list/)

## react组件库
1. [妹子UI](http://t.amazeui.org/#/?_k=0n5yp5)
1. [ant design](http://ant.design/docs/introduce)
1. [material-ui](https://github.com/callemall/material-ui)
1. [react+bootstrap](https://github.com/react-bootstrap/react-bootstrap)

## redux
1. redux 生态清单: [awesome redux](https://github.com/xgrommx/awesome-redux)
1. redux教程推荐: [Full-Stack Redux Tutorial](http://teropa.info/blog/2015/09/10/full-stack-redux-tutorial.html)

## webpack + sass
### webpack sass loader
#### 安装
```
https://github.com/happypeter/react-transform-boilerplate/commit/4c0306d8e8573247d4e6400ebbdb2584e8c2e915
```
#### webpack配置
```
module: {
        loaders: [
          { test: /\.scss$/, loader: 'style!css!autoprefixer!sass' },
        ]
    }
```

## router
* [react-router](https://github.com/reactjs/react-router) 通过react-router来实现路由功能
* [react-router-redux](https://github.com/reactjs/react-router-redux) 跟redux组合在一起使用,把路由也作为状态的一部分

## network
* [fetch](https://github.com/github/fetch)
* [isomorphic-fetch](https://github.com/matthew-andrews/isomorphic-fetch) 前后端同构
* [fetch-jsonp](https://github.com/camsong/fetch-jsonp) 跨域访问


