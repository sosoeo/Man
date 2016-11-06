#### 2016.11.05 zg tobefox@outlook.com

读书笔记。
书名：Javascript入门经典（第六版）
英文名：Phil Ballard: Sams Teach Yourself JavaScript in 24 Hours,Six Edition
目标读者：有Html基本知识和了解的人。

第一章 javascript简介
1. HTML插入代码
   *  在Html中使用<script>...</script>添加代码。
   *  老式格式：<script type="text/javascipt"> ... </script>
2. DOM简介
   *  DOM:Document Object Model,是对文档及其内容的抽象表示。
   *  DOM是web浏览器对web页面的抽象模型，页面的元素具有一个逻辑化层次化的树形结构
   *  DOM模型树形层级结构中，位于最顶端的是window对象。
   *  window对象的子对象有：document,location,history,navigator
   *  document:浏览器加载的任何页面都会创建一个docment对象，包含全部html内容及其显示资源。
   *  window对象及其子对象，或子对象的方法，子对象的属性都是用.逐级引用表示：window.document.title,window.document.body,window.alert()
   *  window由于是DOM的顶级对象，可省洛：window.alert()->alert() window.document.write()->document.write()
3. 练习：exe0.html,exe0.js，end.

第二章 创建简单的脚本
1. 在页面中优先使用<script src="***.js"></script>方式添加javascript代码
2. 注释：// /* */ 变量：字母、数字、下滑线，美元符$ 变量名驼峰大小写
3. 运算符：+-*/ % ++ -- += -= *= /=   字符串连接符+
4. 事件处理器(event handler：为响应用户动作而执行的脚本onClick,onMouseOver,onMouseOut
5. 事件处理器onClick,onMouseOver,onMouseOut发生后可以直接执行javascript脚本而没有<script>声明
6. Html 不区分大小写 XHTML 区分大小写且属性名称一律小写,end.

第三章 使用函数
1. 定义函数：function f(){} 
2. 把函数定义到文档的head部分，就能够确保他们在被调用前已经被定义。
3. 如何从用户input得到一个值然后进行运算。end.


