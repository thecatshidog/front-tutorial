# front-tutorial
this is my frontend notes.

### css notes

#### flexbox布局

1、 [w3c flexbox翻译](https://www.w3.org/html/ig/zh/css-flex-1/#flex-items)

2、 [阮一峰flexbox语法解释](http://www.ruanyifeng.com/blog/2015/07/flex-grammar.html)

#### grid布局

1、 [css书写模式](http://mp.weixin.qq.com/s/NO7FNDqFZIHuKJfj1lIUUA)


### web tools

#### babel

1、[babel中文翻译用户手册](https://github.com/thejameskyle/babel-handbook/blob/master/translations/zh-Hans/user-handbook.md)

2、[babel阮一峰教程](http://www.ruanyifeng.com/blog/2016/01/babel.html)

3、[babel的一些包的作用](http://www.jianshu.com/p/ef80e8a5522b)


#### webpack

1、[webpack中对于样式的处理](https://github.com/zhengweikeng/blog/issues/9)


### javascript

#### 基础

1、[深入js的原型和闭包系列](https://www.kancloud.cn/kancloud/javascript-prototype-closure/66350)：
这篇文章很好地讲解了以下几个点：
- js作用域是静态作用域，函数声明时就已经确定，执行上下文是js预编译，把变量声明，函数赋值，this赋值，参数赋值，arguments等赋值，是动态变化的，根据执行的位置不同而不同。
- this的几种指向情况，全局，函数，call/bind/apply，对象方法调用栈。
- 闭包其实就是某个执行上下文栈里的一个自由变量是用了上面的一个执行上下文栈的，所以我们不能销毁这个执行上下文栈，而导致内存开销变大。
- 原型的基本概念
