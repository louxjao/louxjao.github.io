# js 基础语法

### 数据类型

* Undefined
```
字面值：undefined
```
* Null
```
字面值：null
```

* Boolean
```
字面值：true、false
```

* Number
```
Number.MIN_VALUE = 5e-324
Number.MAX_VALUE = 1.7976931348623157e+308
转换函数：
Number(),
parseInt(),
parseFloat()
```

* String
```
var str1 = 'this is string';
var str2 = "this is string too";
```

* Object
```
var o = new Object();
var o2  = {
    "name":"this is an object",
    "age": 5
};
o2.name = "new name";
o2['name'] = 'new name too';

//对象的遍历
var Obj = {'name':'dog', 'age':3 };
for(var p in Obj){
    console.log(p);// 属性
    console.log(Obj[p]);// 属性值
}
输出：
 name
 dog
 age
 3

```

* Array
```
var arr = new Array();
var arr2 =  new Array(3);
var arr3 = new Array("red","blue","green");
var arr4 = ["red","blue","green"];

arr.length; //数组的长度

//栈方法
arr.push(item ,item2 ,...); //在数组尾部插入
var item = arr.pop(); //在数组尾部尾部

//队列方法
arr.push(item,item2,...);
var item = arr.shift(); //去除队首元素，数组长度减一。

//数组的遍历
var Arr = ['a','b','c'];
//下标的遍历
for(var i in Arr){
    console.log(i);
}
输出：
0
1
2

//下标的遍历
for(var v of Arr){
    console.log(v);
}
输出：
a
b
c
```


