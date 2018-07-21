# javascript高级程序设计 学习笔记
## （一）数据类型
ECMAScript 中有5 种简单数据类型（也称为基本数据类型）：<strong>Undefined、Null、Boolean、Number和String</strong>；<br>
还有 1 种复杂数据类型——<strong>Object</strong>;<br><br>
<img src='https://github.com/xudagongzi/javascript-learning-notes/blob/master/typeof.jpg' width="600" height="300" alt="图片加载失败时，显示这段字"/><br>
需要注意的几点：<br>
1、调用typeof null 会返回"object"，因为特殊值null 被认为是一个空的对象引用<br>
```
var car = null;
alert(typeof car); // "object"
```
2、函数在ECMAScript 中是对象，不是一种数据类型。然而，函数也确实有一些特殊的属性，因此通过typeof 操作符来区分函数和其他对象是有必要的。<br>
3、永远不要测试某个特定的浮点数值。<br><br>
<img src="https://github.com/xudagongzi/javascript-learning-notes/blob/master/float-add.jpg" width="600" height="250" alt="图片加载失败时，显示这段字"/>
