# <center>数据类型检查</center>

## installation

# check
a JavaScript function for check javascript type.

## Installation

You can use this package on the server side as well as the client side.


### [Node.js](http://nodejs.org/):

~~~
npm install types-check
~~~


## API

* isArray:  验证变量类型是否是数组
* isJSON： 验证变量类型是否是json
* isFunction: 验证变量类型是否是函数
* isString: 验证变量类型是否是字符串
* isNumber: 验证变量类型是否是数字
* isUndefined: 验证变量类型是否是undefined
* isNull: 验证变量类型是否是null

  * `data` -- `String`, `Object`, `Array`, `undefined`, `null`, `number` or `Function`
  * returns `Boolean`


## Usage

~~~ javascript
const typesCheck = require('types-check')

console.log(typesCheck.isArray(data));
console.log(typesCheck.isJSON(data));
console.log(typesCheck.isFunction(data));
console.log(typesCheck.isString(data));
console.log(typesCheck.isNumber(data));
console.log(typesCheck.isUndefined(data));
console.log(typesCheck.isNull(data));

~~~