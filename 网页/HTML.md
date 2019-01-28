HTML教程
=======
## 什么是 HTML？

HTML 是用来描述网页的一种语言。

* HTML 指的是超文本标记语言 (Hyper Text Markup Language)

* HTML 不是一种编程语言，而是一种标记语言 (markup language)

* 标记语言是一套标记标签 (markup tag)

* HTML 使用标记标签来描述网页


## HTML 元素语法
* HTML 元素以开始标签起始
* HTML 元素以结束标签终止
* 元素的内容是开始标签与结束标签之间的内容
* 某些HTML元素具有空内容（empty content）
* 空元素在开始标签中进行关闭（以开始标签的结束而结束）
* 大多数 HTML 元素可拥有属性


## HTML 属性
| 属性   | 值               | 描述            |
| ----  | ------           | ------         |
| class | className        | 规定元素的类名    |
| id    | id               | 规定元素的唯一ID  |
| style | style_definition | 规定元素的行内样式 |
| title | text             | 规定元素的额外信息 |
| name  | text             | 规定元素的名字     |

##HTML 标签

HTML 标记标签通常被称为 HTML 标签 (HTML tag)。
* HTML 标签是由尖括号包围的关键词，比如 <html>
* HTML 标签通常是成对出现的，比如 <b> 和 </b>
* 标签对中的第一个标签是开始标签，第二个标签是结束标签
* 开始和结束标签也被称为开放标签和闭合标签
* 不区分大小写（但是推荐使用小写W3C）

## 标签分类
* 块级标签
* 行级标签

#### 块级标签
> 显示为“块”状，浏览器会在其前后显示折行
>> 标题标签（h1~h6）语法：`<h1>`标题`</h1>`
>> 段落标签（p）语法：`<p>`段落`</p>`
>> 水平线标签（hr）语法：`<hr/>`
>> 有序列表标签(数字、字母大小写)
>>> 设置有序标签显示样式 type:`A` `a` `I` `i` `1`

>>>   	 <ol>
>>>  	   <li>列表项<li/>
>>>      </ol>

>> 无序列表标签(圆点、方块、图标)
>>> 设置有序标签显示样式 type: `disc:小圆点` `circle：小实心圆点` `square: 小方块`

>>>   	<ul>
>>>  	   <li>列表项<li/>
>>>      </ul>

<font color=#FF0000>如何去掉style="list-style: none"</font>
    
 


## HTML 标题
HTML 标题（Heading）是通过 `<h1> - <h6>` 等标签进行定义的


