filter  的英文本意是：筛选

### MDN 官方
> The filter() method creates a new array with all elements that pass the test implemented by the provided function.

翻译：filter() 方法会创建一个由符合传入参数测试的所有元素组成的一个数组。

filter()会创建一个有符合筛选条件的数组
例
```js
let a = [1,55,3,6,99,88,74]
let b = a.filter(t=>t>20)
console.log(b);//[55,99,88,74]
```
上面的例子就是筛选出来所有大于20的数，并且创建一个新的数组

### 例如
```js
const words = ["spray", "limit", "elite", "exuberant", "destruction", "present"]

const longWords = words.filter(word => word.length > 6)
```
上面的例子会输出所有的字母数大于6的单词组成的数组。
