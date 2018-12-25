
# javascript 作用域

#### 关于作用域描述
`作用域`顾名思义，作用的`区域/范围`,作用域规定了如何查找一个变量，也确定当前执行代码对`变量的访问权限`。

> 那么我们理解作用域从这2条下手：
> 1.一个`变量`的`作用范围`
> 2.一个变量的`查找规则`，也就是所谓的`作用域链`

#### JavaScript引擎

>下列代码执行结果
```js
  var a = 1;
  console.log(a)
  console.log(2)
  console.log(b)
  //1
  //2
  // Uncaught ReferenceError: b is not defined
```


>下列代码执行结果
```js
  var a = 1;
  console.log(a)
  console.log(2)
  console.log(b;./)
  //Uncaught SyntaxError: missing ) after argument list
```







