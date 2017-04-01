
## 本项目介绍

### 应用场景
搜索框，模糊搜索等


### 理论分析

1. 在搜索框输入关键字
2. 浏览器将关键字「异步」发送给服务器
3. 服务器经过处理。将相应数据以 Json 格式返回客户端
4. 浏览器接受服务器响应数据，解析之后使用 js 操作 dom 显示数据。


重点一：数据交互采用 ajax 方式  
重点二：javascript 解析数据动态展示

### XMLHttpRequest介绍

XMLHttpRequest 是一个API, 它为客户端提供了在客户端和服务器之间传输数据的功能

readyState 五种状态
---
值 |	状态 |	描述
-- | --- |   ----
0	| UNSENT (未打开) |	代理被创建，但尚未调用 open() 方法。
1	| OPENED  (未发送)	| open() 方法已经被调用。
2	| HEADERS_RECEIVED (已获取响应头) | send() 方法已经被调用，并且头部和状态已经可获得。
3 | LOADING (正在下载响应体) |	下载中，responseText 属性已经包含部分数据。
4	| DONE (请求完成)  |	下载操作已完成。
---


### 项目核心源码
见本项目