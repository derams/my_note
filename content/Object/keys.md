
Object.keys 可以把一个对象的所有的 key （属性名）都拿出来，组成一个数组。Object.keys 比 for...in 方法更适合用来做对对象的迭代。

### 例如
```js
const obj = { a: 1, b: 2, c: 3 }

console.log(Object.keys(obj))

Object.keys(obj).map(t => console.log(obj[t]))
```
