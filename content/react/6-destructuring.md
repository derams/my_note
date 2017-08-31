1.解构赋值，是后续我们开发中非常常用的一中赋值方式。他的特点简短易懂，并没有提供什么不能完成的功能，所以可以认为是一种语法糖。

比如我有一个对象：
```js
const obj = { name:'happypeter', b:2, c:3}

let username = obj.name
let bb = obj.b
let cc = obj.c
```
这样我们就可以吧 obj 中的数据，单独赋值给某个变量来使用了，完全不依赖结构赋值
```js
const {username,bb,cc}
```
