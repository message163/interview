# interview
前端面试题汇总`中级`前端

小满 中级前端面试题

自我介绍

CPU 执行原理 以及冯诺依曼体系结构

介绍一下dll 文件

HTML 的字符实体是什么

js底层数据结构如何存储在V8里面

H5新特性

如果提到localstorage 就追问 localstorage API 以及 localStorage 实现原理 以及 localStorage 存在哪儿 以及localStorage 跨域

如果提到PWA技术 就追问 PWA优点  继续追问 Service Workers 继续追问 PWA和hybrid的不同

如果提到canvas 就追问 canvas 常用API

如果提到webSocket 就追问 webSocket 的用法 以及手动实现ws协议 继续追问SSE技术 和 ws的区别

如果提到webWorker 就追问 webWorker 用法 以及实现原理

如何区分强网弱网

什么是灰度

async defer

SEO

BFC

回流与重绘 以及优化方案

webComponents 以及 微前端 以及 emp 模块联邦

Css盒模型 和 怪异盒模型区别 以及统一策略

css 伪类

为什么哔哩哔哩用vmin 不用 vh

css变量

css flex grid

Css 动画 关键帧等

bem架构

如果需要手动写动画，你认为最小时间间隔是多久，为什么？
答：多数显示器默认频率是60Hz，即1秒刷新60次，所以理论上最小间隔为1/60*1000ms＝16.7ms

less scss 解决了什么问题

postCss 是干嘛的 是否用过 是否写过插件

是否用过tailwindCss  是否用过unoCss

typeOf null 是什么 原因是什么

比较两个对象是否相等

判断是不是数组

说说常用的es6 

proxy Reflect 为什么要配合 proxy劫持 函数 劫持for in

迭代器 生成器 for of  以及 Iterator  以及数组解构原理 和对象解构原理（深入V8引擎）

Class 用法 super原理 继承  如何定义私有属性

AMD CMD UMD CJS  ESM  IIFE 的区别

Promise 静态方法 以及 all 实现原理 有限状态机

map set weakMap  weakSet 

微任务 宏任务 同步 异步  async  await

装饰器 以及 装饰器解决了什么问题

ArrayBuffer 如何使用 以及跟webGl 的关系

讲一下 GLSL Shader 实现亮度(Brightness)、对比度(Contrast) 和边缘检测(Edge Detection) 是如何实现的回答的时候忘记了对比度的算法实现没答上来，讲了下明度 Luminance 的调节；亮度Brightness是RGB+亮度系数；边缘检测和图像锐化是使用 Convolution Kernel 卷积核加深中心像素与周围像素的色彩差值梯度，使边缘更加突出

计算机图形绘制原理 

WebAssembly 工作原理   如何编译成wasm

webRTC 架构 如何 实现推流 拉流

垃圾回收 内存泄漏 堆栈

深拷贝 防抖 节流 

实现深拷贝的几种方法 追问 对象群嵌套15层 我想用14层的一个属性 最优解决方案 引出 Immutable js 追问 Immutable js 实现原理 字典 位分区 及 树压缩算法

什么是纯函数 什么是副作用函数

浏览器输入一个url 发生了什么 DNS解析顺序  追问OSI 七层网络模型 三次握手 http https 区别 http1 2 3 区别 强缓存 协商缓存

TCP 跟 UDP 的区别 

TCP 的 超时重传协议 滑动窗口思想

Ajax fetch  navigator.sendBeacon  三个的区别

nodejs 是否用过

是否用过一些库 如 express koa  nest  追问用的什么数据库 以及高速缓存 如 redis ，用的什么ORM框架，如果熟悉express 追问 中间件原理，熟悉nest 追问 ioc控制反转 DI 依赖注入 设计模式  以及MVC 架构 和MVVM 区别 继续追问nest rxjs 库用法 以及原理 继续追问nest 微服务 gRPC MQ 以及网关 。

聊聊数据库 mysql 底层数据结构 为什么使用B+ 树，继续追问 mysql事务以及四大特性  追问悲观锁和乐观锁

聊聊redis  redis是单线程还是多线程 以及底层原理

聊聊nodejs 的 vm虚拟机 以及PAI  以及 底层libuv openSSL

聊聊nodejs 子线程 进程守卫怎么做

聊聊 断点续传怎么做（前后端）

Npm 是什么  package-lock.json 是做什么的 npm 缓存原理

pnpm 实现原理 以及 monorepo 架构

如何发布 npm 包 有没有发过 自己的 npm包  周下载量多少

webpack  vite rollup esbuild swc gulp

Webpack 脱口而出的配置 webpack 分包  webpack 打包优化    webpack打包原理 以及 HMR 原理

Vite原理 中间件原理  是否写过vite插件 

rollup 和 webpack的区别 

esBuild 常用命令 以及 为什么这么快 

Vue2 3 区别

Diff算法  追问 最长递增子序列算法  以及 二分查找 和 贪心算法

响应式原理 追问 为什么使用位运算

Vue源码调度机制 以及nextTick执行机制

Vue3 新增2个内置组件 介绍

Vue3 keep-alive LRU 算法以及原理介绍

Vue-router 原理 hash 和 history 以及 对应微前端 以及monorepo 架构

Pinia vuex 设计模式 以及实现原理 为什么刷新数据丢失 以及解决方案

AOT 和 JIT 的区别

动态扩容 动态缩容 横向扩容 怎么做

nginx 四层LB负载均衡 nginx七层LSB 负载均衡怎么做 nginx多机房异地容灾怎么做

nginx源码中的unix域是怎么做的 做什么的

nginx lua插件怎么写

网关怎么做 网关熔断怎么做 网关分流怎么做 网关加密怎么做

FPS 帧率 requestIdleCallback performance



