# markdown 基本语法

# 表格

<table>
<p style="text-align:center ">功课表</p>
    <tr>
      <th>语文</th>
      <td>7:00-7:40</td>
      <td>7:50-8:30</td>
    </tr>
   <tr>
      <th>数学</th>
      <td>7:00-7:40</td>
      <td>7:50-8:30</td>
    </tr>
    <tr>
      <th>英文</th>
      <td>7:00-7:40</td>
      <td>7:50-8:30</td>
    </tr>
</table>

或者 从[tablesgenerator][tablesgenerator]复制

| 语文  | 7:00-7:40 | 7:50-8:30 |
|-------|-----------|-----------|
| 数学  | 7:00-7:40 | 7:50-8:30 |
| 英文  | 7:00-7:40 | 7:50-8:30 |

# 表格图片

<table>
    <tr>
        <td>
        <img width="200" class='im-speaker-pic' src='/images/1.jpg' alt='1'>
        </td>
        <td>
        <img width="200" class='im-speaker-pic' src='/images/2.jpg' alt='2'>
        </td>
    </tr>
    <tr>
        <td><a href='https://lidayuls.github.io/'>Dayu Li</a> <br>
        Shanxi University</td>
        <td> ... </td>
    </tr>
</table>


# 链接

Dayu Li's Homepage [here][homepage]

# 图片

两种方式

    第一种方式： ![1][pic1]
    
![1][pic1]

    第二种方式： <img src="/images/1.jpg" width="30%"/>
<img src="/images/1.jpg" width="30%"/>


# 注释
<!-- 这是个注释 -->

# 引用

    引用tab缩进就可以


# 公式

GitHub Flavored Markdown 曾经是支持 LaTeX 的，但是现在不支持了……因此若想在 README 或者评论中插入数学公式，就得使用另外的方式。
CodeCogs 提供了一个[在线 LaTeX 编辑器][eqneditor]，可以将输入的数学公式转换为图片，并自动生成 HTML 代码（也支持其他格式）。复制其HTML代码即可。

或者生成 URL_encoded 然后设置url引用成图片即可

<a href="https://www.codecogs.com/eqnedit.php?latex=p(x|y)&space;=&space;\frac{{p(x,y)}}{{p(y)}}&space;=&space;\frac{{p(y|x)p(x)}}{{p(y)}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?p(x|y)&space;=&space;\frac{{p(x,y)}}{{p(y)}}&space;=&space;\frac{{p(y|x)p(x)}}{{p(y)}}" title="p(x|y) = \frac{{p(x,y)}}{{p(y)}} = \frac{{p(y|x)p(x)}}{{p(y)}}" /></a>

<img src="https://latex.codecogs.com/gif.latex?p(x|y)&space;=&space;\frac{{p(x,y)}}{{p(y)}}&space;=&space;\frac{{p(y|x)p(x)}}{{p(y)}}" title="p(x|y) = \frac{{p(x,y)}}{{p(y)}} = \frac{{p(y|x)p(x)}}{{p(y)}}" />

![formula][formula]

![formula_encoded][formula_encoded]

[pic1]:/images/1.jpg
[homepage]:https://lidayuls.github.io/
[tablesgenerator]:http://www.tablesgenerator.com/markdown_tables
[eqneditor]:https://www.codecogs.com/latex/eqneditor.php
[formula]:https://latex.codecogs.com/gif.latex?p(x|y)&space;=&space;\frac{{p(x,y)}}{{p(y)}}&space;=&space;\frac{{p(y|x)p(x)}}{{p(y)}}
[formula_encoded]:https://latex.codecogs.com/gif.latex?p%28x%7Cy%29%20%3D%20%5Cfrac%7B%7Bp%28x%2Cy%29%7D%7D%7B%7Bp%28y%29%7D%7D%20%3D%20%5Cfrac%7B%7Bp%28y%7Cx%29p%28x%29%7D%7D%7B%7Bp%28y%29%7D%7D
    [pic1]:/images/1.jpg
    [homepage]:https://lidayuls.github.io/
    [tablesgenerator]:http://www.tablesgenerator.com/markdown_tables
    [eqneditor]:https://www.codecogs.com/latex/eqneditor.php

