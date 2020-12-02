# 路由

需要使用 react路由，需要 react-router  、 react-router-dom

# react-router 与 react-router-dom 的区别

> react-router-dom 是基于 react-router 做的一个二次封装。提供了一些react-router没有的组件，比如 Link NavLink 。

# BrowserRouter 与 HashRouter

> 这两个都是 react-router-dom 提供的组件。都是代表着路由的基础。react中必须选择这两个中某一个放置在根元素上面（路由相关的组件 Link ... 必须包裹在当前这两个组件的里面, 一个项目中只能出现一次）

区别就可以看成是，vue的两种不同的模式。
BrowserRouter - history
HashRouter - hash

# Route

> 这个是 react-router 中提供的组件， 一个路由，并且他还是个坑。


# Link

> 提供导航相关。


# 使用步骤
1. 安装 react-router-dom
2. 哪里要用，写哪里。
