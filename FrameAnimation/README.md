### 参考慕课网教程，原生JS实现帧动画库 [demo访问这里](http://kad0108.github.io/FE-Demos/FrameAnimation/demo/demo.html)
### 学习到的知识点：
* 常用帧动画方式及对比，CSS vs JS
* 模块化，webpack，闭包（this的指向是由它所在函数调用的上下文决定的，而不是由它所在函数定义的上下文决定的）
* 书写规范（原型链私有方法的命名，'use strict'），方法加注解(@constructor、@private、@param)
* 一些js小方法， 比如 |0 表示向下取整，+new Date()相当于调用date.getTime()拿到当前时间的毫秒数且性能好
* 教程中是用webpack自带的server插件（实际上就是用NodeJS创建了一个server）运行，我自己尝试了用NodeJs运行，需要在运行文件根目录下添加 *server.js* 文件，命令 *node server.js* 即可访问
* 设计思想值得一段时间后回过头来再看一遍