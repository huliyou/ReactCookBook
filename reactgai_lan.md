# React概览

React 的核心思想是：组件化、状态机。

各个组件维护自己的状态和UI，当状态变更，自动重新渲染整个组件。

React 大体包含下面这些概念：
* Component
* JSX
* Virtual DOM
* Data Flow

```
import React, { Component } from  'react' ;
 import { render } from  'react-dom' ;

class  HelloMessage  extends  Component  {
  render() {
    return  < div > Hello {this.props.name} </ div > ;
  }
}

//加载组件到DOM元素mountNode 
render( < HelloMessage  name = "John" /> , mountNode);
```

## 可复用组件
设计接口的时候，把通用的设计元素（按钮，表单框，布局组件等）拆成接口良好定义的可复用的组件。这样，下次开发相同界面程序时就可以写更少的代码，也意义着更高的开发效率，更少的 Bug 和更少的程序体积。

## JSX
JSX is a JavaScript syntax extension that looks similar to XML. You can use a simple JSX syntactic transform with React.

[jsx-in-depth](https://facebook.github.io/react/docs/jsx-in-depth.html)

## Virtual DOM
当组件状态```state```有更改的时候，React会自动调用组件的```render```方法重新渲染整个组件的UI。

当然如果真的这样大面积的操作DOM，性能会是一个很大的问题，所以React实现了一个Virtual DOM，组件DOM结构就是映射到这个Virtual DOM上，React在这个Virtual DOM上实现了一个diff算法，当要重新渲染组件的时候，会通过diff寻找到要变更的DOM节点，再把这个修改更新到浏览器实际的DOM节点上，所以实际上不是真的渲染整个DOM树。这个Virtual DOM是一个纯粹的JS数据结构，所以性能会比原生DOM快很多。+

## Data Flow
“单向数据绑定”是React 推崇的一种应用架构的方式。当应用足够复杂时才能体会到它的好处,而且复杂项目中，你能轻易发现导致bug的原因。
