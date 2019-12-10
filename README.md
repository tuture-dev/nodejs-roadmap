# Node.js 学习路径

## 目录

- [Node.js 学习路径](#nodejs-%e5%ad%a6%e4%b9%a0%e8%b7%af%e5%be%84)
  - [目录](#%e7%9b%ae%e5%bd%95)
  - [入门](#%e5%85%a5%e9%97%a8)
    - [JavaScript 语言基础](#javascript-%e8%af%ad%e8%a8%80%e5%9f%ba%e7%a1%80)
      - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9)
      - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90)
    - [Node 基础](#node-%e5%9f%ba%e7%a1%80)
      - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-1)
      - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b)
      - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-1)
    - [HTTP 协议](#http-%e5%8d%8f%e8%ae%ae)
      - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-2)
      - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-2)
  - [进阶](#%e8%bf%9b%e9%98%b6)
    - [异步编程](#%e5%bc%82%e6%ad%a5%e7%bc%96%e7%a8%8b)
      - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-3)
      - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-1)
      - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-3)
    - [Web 后端开发](#web-%e5%90%8e%e7%ab%af%e5%bc%80%e5%8f%91)
      - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-4)
      - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-2)
      - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-4)
    - [自动化测试](#%e8%87%aa%e5%8a%a8%e5%8c%96%e6%b5%8b%e8%af%95)
      - [知识点](#%e7%9f%a5%e8%af%86%e7%82%b9-5)
      - [实战教程](#%e5%ae%9e%e6%88%98%e6%95%99%e7%a8%8b-3)
      - [参考资源](#%e5%8f%82%e8%80%83%e8%b5%84%e6%ba%90-5)
    - [实时应用开发](#%e5%ae%9e%e6%97%b6%e5%ba%94%e7%94%a8%e5%bc%80%e5%8f%91)
    - [应用部署](#%e5%ba%94%e7%94%a8%e9%83%a8%e7%bd%b2)
  - [前沿](#%e5%89%8d%e6%b2%bf)
    - [GraphQL 服务开发](#graphql-%e6%9c%8d%e5%8a%a1%e5%bc%80%e5%8f%91)

## 入门

<div align="center">
<img width="100" height="100" src="./assets/images/javascript.svg" />

### JavaScript 语言基础
</div>

> JavaScript ( JS ) 是一种具有函数优先的轻量级，解释型或即时编译型的编程语言。虽然它是作为开发Web 页面的脚本语言而出名的，但是它也被用到了很多非浏览器环境中，例如 Node.js、 Apache CouchDB 和 Adobe Acrobat。JavaScript 是一种基于原型编程、多范式的动态脚本语言，并且支持面向对象、命令式和声明式（如函数式编程）风格。了解更多 JavaScript。

#### 知识点

1. JavaScript 语法要素
    - 各类语句
      - 循环语句
      - 条件语句
      - Switch 语句
    - 变量与操作符
    - 函数定义
2. JavaScript 数据类型
    - 五类基本数据类型
      - string
      - number
      - boolean
      - object
      - function
    - 三类object
      - Object
      - Date
      - Array
    - 两类空值
      - undefined
      - null
3. ECMAScript 6+ 基础知识
    - let & const 变量声明
    - 箭头函数
    - 对象 & 数组解构赋值
    - class 的基本语法和继承
    - Promise 对象

#### 参考资源

- [MDN - JavaScript 基础](https://developer.mozilla.org/zh-CN/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [W3schools JavaScript 教程](https://www.quanzhanketang.com/js/default.html)（英文）
- [阮一峰《ECMAScript 6 入门》](http://es6.ruanyifeng.com/)

---

<div align="center">
<br/>
<img width="100" height="100" src="./assets/images/nodejs.svg" />

### Node 基础
</div>

> 简单的说 Node.js 就是运行在服务端的 JavaScript。 Node.js 是一个基于Chrome JavaScript 运行时建立的一个平台。 Node.js是一个事件驱动I/O服务端JavaScript环境，基于Google的V8引擎，V8引擎执行Javascript的速度非常快，性能非常好。

#### 知识点

1. 安装
    - 各平台安装包
    - nvm
2. 编辑器环境安装
    - VSCode
    - ESLint
    - Prettier
3. 模块机制
    - CommonJS 规范
    - require、module 和 exports
4. npm
    - 基本命令
    - package.json
    - 切换 npm 源
    - npm scripts
5. 全局对象
    - process 对象
    - Buffer 对象

#### 实战教程

- ✍️《Node.js 开发环境搭建》 *🗝知识点 1、2、4*
- ✅[《Node.js 快速入门教程》](https://tuture.co/2019/12/03/892fa12/) *🗝知识点 3、4、5*

#### 参考资源

- [VSCode JavaScript 语言开发官方文档](https://code.visualstudio.com/docs/languages/javascript)
- [狼叔：如何正确的学习Node.js - 安装Node.js环境](https://i5ting.github.io/How-to-learn-node-correctly/#10302)
- [《Node.js技术栈》- Node.js基础系列](https://www.nodejs.red/#/nodejs/base/what-is-nodejs)
- [《Node.js技术栈》- Module模块机制](https://www.nodejs.red/#/nodejs/module)

---

<div align="center">
<br/>
<img width="100" height="100" src="./assets/images/http.svg" />


### HTTP 协议
</div>

> HTTP是一种能够获取如 HTML 这样的网络资源的 protocol(通讯协议)。它是在 Web 上进行数据交换的基础，是一种 client-server 协议，也就是说，请求通常是由像浏览器这样的接受方发起的。一个完整的Web文档通常是由不同的子文档拼接而成的，像是文本、布局描述、图片、视频、脚本等等。

#### 知识点

1. HTTP 的概念
2. HTTP 的特点
    - 无连接
    - 无状态
3. 客户端向服务端发起请求的过程
    - 三次握手
4. 请求报文的内容格式
    - 请求方法（GET、POST、PUT 等等）
    - 请求路径（URL/URI）
    - 请求头部及常见字段
5. 响应报文的内容格式
    - 状态码
    - 响应头部及常见字段
6. 常见的数据交换格式
    - JSON
    - Form 表单数据
    - XML

#### 参考资源

- [MDN - HTTP 概述](https://developer.mozilla.org/zh-CN/docs/Web/HTTP/Overview)
- [十分钟搞懂 HTTP 和 HTTPS 协议](https://zhuanlan.zhihu.com/p/72616216)
- [阮一峰 - HTTP 协议入门](http://www.ruanyifeng.com/blog/2016/08/http.html)

## 进阶

<div align="center">
<img width="100" height="100" src="./assets/images/promises.svg" />

### 异步编程
</div>

#### 知识点

1. 异步 I/O 与原生事件循环
2. 回调函数，以及 async 库的优化
3. Promise 与 async/await
4. 性能测试与调优

#### 实战教程

- ✍️《Node.js 异步编程实战》 🗝知识点 1、2、3、4

#### 参考资源

- [狼叔：如何正确的学习Node.js - Node核心：异步流程控制](https://i5ting.github.io/How-to-learn-node-correctly/#10306)
- [async 官方文档](http://caolan.github.io/async/v3/)（英文）
- [MDN - 使用 Promise](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Guide/Using_promises)
- [MDN - async 函数](https://developer.mozilla.org/zh-CN/docs/Web/JavaScript/Reference/Statements/async_function)
- [JavaScript Promise迷你书](http://liubin.org/promises-book/)

---

<div align="center">
<br>
<img width="100" height="100" style="padding-right: 20px" src="./assets/images/express.svg" />
<img width="100" height="100" src="./assets/images/koa.svg" />

### Web 后端开发
</div>

> 凭借优秀的 I/O 性能和吞吐率， Node.js 当之无愧是 Web 服务器开发的首选之一。后端开发常用框架包括 Express 和 Koa，可任选其一进行学习。

#### 知识点

1. 路由的概念与定义
2. 中间件的编写与使用
3. 模板引擎的使用
4. RESTful API 的开发
5. 关系型数据库的接入（例如 MySQL）
6. 文档型数据库的接入（例如 MongoDB）

#### 实战教程

- ✅[《Express 快速入门教程》](https://tuture.co/2019/11/26/cd5b993/) 🗝知识点 1, 2, 3
- ✍️《Koa 快速入门教程》 🗝知识点 1, 2, 3
- ✅[《从零开始用 Express + MongoDB 搭建图片分享社区（一）》](https://tuture.co/2019/10/16/a0531f0/) 🗝知识点 1, 2, 3
- ✅[《从零开始用 Express + MongoDB 搭建图片分享社区（二）》](https://tuture.co/2019/10/16/29f41c0/) 🗝知识点 1, 2, 3, 6

#### 参考资源

- [Express 官方文档](http://expressjs.com/)（英文）
- [MDN - Express 网页框架 (node.js/JavaScript)](https://developer.mozilla.org/zh-CN/docs/Learn/Server-side/Express_Nodejs)
- [Koa 中文文档](https://github.com/guo-yu/koa-guide)
- [Koa2 进阶学习笔记](https://chenshenhai.github.io/koa2-note/)

---

<div align="center">
<br/>
<img width="100" height="100" src="./assets/images/mocha.svg" />
<img width="100" height="100" src="./assets/images/chai.svg" />
<img width="100" height="100" src="./assets/images/jest.svg" />

### 自动化测试
</div>

#### 知识点

1. 单元测试
2. 基准测试
3. 持续集成
    - Travis CI
    - Circle CI
    - GitHub Action

#### 实战教程

- ✍️《Mocha + Chai 测试 Express 应用》 🗝知识点 1, 3

#### 参考资源

- [阮一峰 - 测试框架 Mocha 实例教程](http://www.ruanyifeng.com/blog/2015/12/a-mocha-tutorial-of-examples.html)

---

<div align="center">
<br/>
<img width="100" height="100" src="./assets/images/socket.io.svg" />

### 实时应用开发
</div>

🛠 筹备中，敬请期待。

---

<div align="center">
<br/>
<img width="100" height="100" style="padding: 5px" src="./assets/images/pm2.svg" />
<img width="100" height="100" style="padding: 5px" src="./assets/images/docker-icon.svg" />
<img width="100" height="100" src="./assets/images/kubernetes.svg" />

### 应用部署
</div>

🛠 筹备中，敬请期待。

## 前沿

<div align="center">
<br/>
<img width="100" height="100" style="padding: 5px" src="./assets/images/graphql.svg" />
<img width="100" height="100" style="padding: 5px" src="./assets/images/prisma.svg" />
<img width="100" height="100" src="./assets/images/apollostack.svg" />

### GraphQL 服务开发
</div>

🛠 筹备中，敬请期待。
