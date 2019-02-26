HTML教程
=======
## 什么是 HTML？

HTML 是用来描述网页的一种语言。

* HTML 指的是超文本标记语言 (Hyper Text Markup Language)

* HTML 不是一种编程语言，而是一种标记语言 (markup language)

* 标记语言是一套标记标签 (markup tag)

* HTML 使用标记标签来描述网页

## HTML结构
* html
* head
* title
* body

## HTML 元素语法
* HTML 元素以开始标签起始
* HTML 元素以结束标签终止
* 元素的内容是开始标签与结束标签之间的内容
* 某些HTML元素具有空内容（empty content）
* 空元素在开始标签中进行关闭（以开始标签的结束而结束）
* 大多数 HTML 元素可拥有属性
* 当浏览器遇到两个或者两个以上的连续空格时,只将其显示为一个空格,同样,当遇到一次换行时,浏览器也会将其看作一个空格,这一特性称为白色空间折叠


## HTML 属性
| 属性   | 值               | 描述            |
| ----  | ------           | ------         |
| class | className        | 规定元素的类名    |
| id    | id               | 规定元素的唯一ID  |
| style | style_definition | 规定元素的行内样式 |
| title | text             | 规定元素的额外信息 |
| name  | text             | 规定元素的名字     |

## HTML 标签

HTML 标记标签通常被称为 HTML 标签 (HTML tag)。
* HTML 标签是由尖括号包围的关键词，比如 `<html>`
* HTML 标签通常是成对出现的，比如 `<div>` 和 `</div>`
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

>> 换行符  `<br/>`

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

`如何去掉样式：style="list-style: none"`

>> 定义描述标签的语法

>>>  	<dl>
>>>   	      <dt>标题</dt>
>>>   	      <dd>描述1</dd>
>>>   	</dl>

>> 分区标签（div+css布局）俗称：盒子

>>>      <div>头部</div>
>>>      <div>内容</div>
>>>      <div>底部</div>

#### 行级标签

> 按行逐一显示。前后不会自动换行

##### 文本格式化元素

`<b>	 定义粗体文本`

`<big>	 定义大号字`
 
`<em>	 定义着重文字`
 
`<i>	 定义斜体字` 

`<strong>  表示其内容十分重要 在浏览器上显示为粗体`

`<small> 定义小号字` 

`<sub>   定义下标文字` 

`<sup>	 定义上标文字` 

#### 超链接标签

    <a href="链接地址" target=“目标窗口”>链接文本或图片</a>
    常用属性：
    （1）href 指定超链接所关联的另一个资源
         mailto:建立email链接
         还可以跳转到本页某一个定义一个id标签处
    （2）target
    | 属性    | 描述           |
    | _blank | 在新窗口打开连接  |
    | _self   | 在本窗口打开连接 |
    
#### 图像标签 `<img src="图片地址" alt=“图像无法加载的时候的提示文字” title="附加信息">`
#### 特殊强调标签 `<span>文本等行级内容</span>`
#### 换行标签 `<br/>`
#### 常用的特殊符号：
*  空格	 `&nbsp;`
*  大于	 `&gt;`
*  小于	 `&lt;`
*  引号	 `&quot;`
*  版权号 `&copy;`

#### 表格相关元素

```
<table>
    <tr>
        <td>表头</td>
        <td>表头</td>
        <td>表头</td>
    </tr>
    <tr>
        <td>内容单元格</td>
        <td>内容单元格</td>
        <td><a href="http://www.baidu.com">操作</td>
    </tr>
    <tr>
        <td>内容单元格</td>
        <td>内容单元格</td>
        <td><a href="http://www.baidu.com">操作</td>
    </tr>
    <tr>
        <td>内容单元格</td>
        <td>内容单元格</td>
        <td><a href="http://www.baidu.com">操作</td>
    </tr>
    <tr>
        <td>内容单元格</td>
        <td>内容单元格</td>
        <td><a href="http://www.baidu.com">操作</td>
    </tr>
    <tr >
        <td>总计</td>
        <td colspan="2">1000</td><!--横向跨越的列数-->
    </tr>
</table>
```
###### 用在td上 colspan 用来指定合并行数 rowspan 用来指定合并列数

#### 表单标签

* form标签 

    > action：指定表单提交后由服务器上的哪个处理程序进行处理
    
    > method：指定向服务器提交的方式一般为get和post两种方法
* 单行文本框  `<input type="text" maxlength="" name=""/>`
* 密码框  `<input type="password" maxlength="" name=""/>`
* 文本域  `<textarea cols="列" rows="行" name=""/>`   
* 单选按钮  `<input type="radio"  value="" name="" checked="checked"/>`
* 复选框  `<input type="checkbox" name="" values="" checked="checked"/>`
* 下拉列表框
```
<select name="">
    <option selected="selected" value=""></option>
</select>
```
* 对选框:
```
<select name="" multiple="multiple">
    <option selected="selected" value="">ddd</option>
</select>
```
* 文件上传域 `<input type="file">`
* 图像按钮`<input type="image" name="assa" src="images/settled.png" width="100" height="20">`
* 按钮 `<button>按钮</button>`
* 隐藏控件 `<input type="hidden">`
* html5 表单验证   required="required"

#### 视频
`<video src="" poster="" width="" height="" controls="controls" autoplay="autoplay" loop="loop" preload="auto"></video>`
* poster:在视频加载时或在视频播放之前,还特性用于指定在播放中显示一个图像
* controls:表示浏览器需要提供默认的播放控件
* autoplay:表示视频文件应该自动播放
* loop:就表示循环播放
* preload:在页面加载时需要做什么,其有三个可选值:
>>> none:该值表示在用户按下播放按钮之前,浏览器不必加载视频

>>> auto:该值表示浏览器应该在页面加载时载入视频

>>> metadata:该值表示浏览器只需要收集少量视频信息,比如大小,首帧图像,播放列表和持续时间

### 音频

`<audio src=""></audio>`

添加多个音频源:
```
<audio src="">  
   <source src="">
</audio>
```

