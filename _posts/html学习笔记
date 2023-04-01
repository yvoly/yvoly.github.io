---
layout: post
title: "html学习笔记"
date: 2023-04-01
---
# HTML基本结构

```

<!DOCTYPE html>

<html>

<head>     

<meta charset="utf-8">

<title>标题</title> 

</head>

<body>

</body>

</html>

```

- `<!DOCTYPE>`文档类型声明

- `<html>`HTML 页面的根元素

- `<head>`包含文档的元（meta）数据，如

- `<meta charset="utf-8">`定义网页编码格式为utf-8

- `<title>`描述文档的标题

- `<body>`包含可见的页面内容

# HTML标签

## `h`标题

```

<h1>这是一级标题</h1>

<h2>这是二级标题</h2>

<h3>这是三级标题</h3>

<h4>这是四级标题</h4>

<h5>这是五级标题</h5>

<h6>这是六级标题</h6>

```

## `br`换行

```

这<br>就是<br>换<br>行

```

## `p`段落

```

<p>这是一个段落。</p>

<p>这是另外一个段落。</p>

<!-- 段落之间有空行，换行没有 -->

```

## `hr`水平线

```

<hr>

```

## `div` `span`区块元素

```

<div></div>

```

## `strong` `b`文字粗体

```

<strong>粗体</strong>

```

## `em` `i`文字斜体

```

<em>斜体</em>

```

## `del` `s`文字删除线

```

<del>删除线</del>

```

## `ins` `u`文字下划线

```

<ins>下划线</ins>

```

## `sup`上标

```

a<sup>2</sup>+b<sup>2</sup>=c<sup>2</sup>

a²+b²=c²

```

## `sub`下标

```

H<sub>2</sub>O

```

## `a`链接

```

<a href="url" target="目标窗口的弹出方式">文本或图像或#id或#</a>

```

- `target="_self"`当前窗口打开

- `target="_blank"`新窗口打开

### 锚点链接

```

<a id="tips">有用的提示部分</a>

<a href="#tips">访问有用的提示部分</a>

img 图像

<img src="yvoly.jpg" alt="图片损坏了(*_*) title="这是我的头像哦" width="300" height="300" border="3"/>

```

- `alt`图像不能显示时的替换文本

- `title`鼠标悬停时显示的内容

- `width`设置图像宽度

- `height`设置图像高度

（width 和 height 中只需设置一个，图片便会按比例缩放）

- `border`设置图像边框的宽度

## `<!-- -->`注释

```

<!-- 这是一个注释 -->

```

## `table`表格

```

<table>

<caption>轻音少女</caption>

<tr>

<th>姓名</th>

<th>性别</th>

<th>生日</th>

</tr>

<tr>

<td>平泽唯</td>

<td>女</td>

<td>11月27日</td>

</tr>

<tr>

<td>平泽忧</td>

<td>女</td>

<td>2月22日</td>

</tr>

</table>

```

- `table`定义一个表格标签

- `caption`表格标题

- `tr`表格中的行，嵌套在`table`中

- `th`表头单元格标签，嵌套在`tr`中

- `td`表格中的单元格，嵌套在`tr`中

### 合并单元格

（其实说是“扩大”更合适，多了的单元格要删除）

```

<table border="1"> 

<tbody>

<tr> 

<td colspan="2">🍇</td> 

<td rowspan="2">🍓</td> 

</tr> 

<tr> 

<td>🍎</td> 

<td>🍉</td> 

</tr> 

</tbody>

</table>  

```

- `rowspan="`合并单元格的个数" 跨行（竖着）合并

- `colspan="`合并单元格的个数" 跨列（横着）合并

## 列表

### `ul`无序列表

```

<ul>

<li>🍉</li>

<li>🍎</li>

</ul>

```

### `ol`有序列表

```

<ol>

<li>🍉</li>

<li>🍎</li>

</ol>

```

### `dl`自定义列表

```

<dl>

<dt>名词1</dt>

<dd>名词1解释1</dd>

<dd>名词1解释2</dd>

<dt>名词2</dt>

<dd>名词2解释1</dd>

<dd>名词2解释2</dd>

</dl>

```

## `form`表单

### `input`输入表单元素`type`属性

```

<form>

<input type="属性值">

</form>

```

#### `text`文本域

```

昵称：<input type="text" name="昵称" value="请输入用户名"><br>

简介：<input type="text" name="简介" value="请输入简介">

```

- `name`必写

- `value`输入框中显示的初始值（输入时需清除），也是提交给服务器的值

#### `password`密码字段

```

密码：<input type="password" name="密码"> 

```

- `name`必写

- `value`输入框中显示的初始值（但是看不见），也是提交给服务器的值

#### `radio`单选按钮

```

<input type="radio" name="性别" value="男">男 

<input type="radio" name="性别" value="女">女 

```

- 有相同的``name`值才能实现单选效果，必写

- `value`提交给服务器的值

#### `checkbox`复选框

```

<input type="checkbox" name="饭" value="早饭">早饭 

<input type="checkbox" name="饭" value="中饭">中饭

<input type="checkbox" name="饭" value="晚饭">晚饭 

```

- 复选框也要有相同的`name`值，必写

- `value`提交给服务器的值

#### `button`普通按钮

```

<input type="button" value="获取验证码">

value 按钮上显示的文本

```

#### `submit`提交按钮

```

昵称：<input type="text" name="昵称"> 

<input type="submit" value="提交">

```

- `value`按钮上显示的文本

#### `reset`重置按钮

```

<input type="reset" value="重置">

```

- `value`按钮上显示的文本

#### `image`图像形式的提交按钮

```

上传头像：<input type="image">

```

#### `file`文件域

```

上传文件：<input type="file"> 

```

`checked`默认选中

```

<input type="radio" name="性别" value="男" checked>男 

<input type="radio" name="性别" value="女">女 

<input type="checkbox" name="饭" value="早饭" checked>早饭 

<input type="checkbox" name="饭" value="中饭" checked>中饭

<input type="checkbox" name="饭" value="晚饭">晚饭 

```

`maxlength`控件允许输入的最多字符数

```

昵称（最多6字符）：<input type="text" name="昵称" value="请输入用户名" maxlength="6">

```

`label`绑定表单元素

```

<label> <input type="radio" name="性别" value="男">男</label>

<label> <input type="radio" name="性别" value="女">女</label>

```

```

<input type="radio" name="性别" value="男" id="男"><label for="男">男</label> 

<input type="radio" name="性别" value="女" id="女"><label for="女">女</label> 

```

### `textarea`文本域

```

给我留言吧！<textarea></textarea>

```

### `select`下拉表单元素

```

<select>

<option>选项1</option>

<option selected>选项2</option>

<option>选项3</option>

</select>

```

- `selected`默认选中

# 其他知识

## 路径

- `/`到上一级目录

- `../`到下一级目录

## 特殊字符

|字符|描述|实体名称|实体数字|

|---|---|---|---|

| |空格|`＆nbsp;`|`&#160;`|

|<|小于号|`&lt;`|`&#60;`|

|>|大于号|`&gt;`|`&#62;`|

|&|和号|`&amp;`|`&#38;`|

|©|版权标志|`&copy;`|`&#169;`|

