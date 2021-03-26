
### 1.标题

# MD_Heading level 1
<h1>HTML_Heading level 1</h1>

##### MD_Heading level 6
<h6>HTML_Heading level 6</h6>

MD_Heading level 1
===============
MD_Heading level 2
---------------
**Note:==必须加空行, md标题前有空行**

***

### 2.段落
md_P1

md_P2

<p>HTML_P1</p>
<p>HTML_P2</p>

P1(后面有两个以上空格)  
P2
<p>P1<br>P2</p>

---

### 3.文字处理
- 加粗  
  **md_加粗1**  
  __md_加粗2__  
  <strong>HTML_加粗</strong>   

- 斜体  
  *md_斜体1*  
  _md_斜体2_  
  <em>HTML_斜体</em>   
- 加粗的斜体  
    ***md_粗斜体1***  
    ___md_粗斜体2___  
    <strong><em>HTML_粗斜体</em></strong>

---

### 4.块引用
>加个>
>
>可空行
>>也可嵌套
> - ###### 可加标题，文字处理

---

### 5. 清单列表
- 有序  
1. MD_1
2. MD_2
1. MD_3 注意：与开头数字无关  
4. MD_4

<ol>
<li>HTML_1</li>
<li>HTML_2</li>
<li>HTML_3</li>
<li>HTML_4</li>
</ol>

- 无序


+ MD_1  
* MD_2
- MD_3 注意 +-*都行
  + MD_4 多空行保格式

<ul>
<li>HTML_1</li>
<li>HTML_2</li>
<li>HTML_3</li>
  <ul>
  <li>HTML_4</li>
  </ul>
</ul>

---
### 6. 代码块和代码
```
<html>
  <head>
    <title>Test</title>
  </head>  
```

    <html>
      <head>
        <title>Test</title>
      </head>
注意：HTML这里要缩进两个Tab，并且前空行（四个空格）

- 单个引用  
`MD`
<code>HTML</code>
- 如果存在\`符号用两个\`\`将它包起来  
  ``A`B`C``
---
### 7. 图片
- 网络之间用  
![测试](http://img.adoutu.com/picture/1539788237105.jpg "Testing")  
- 本地  
![测试](./图片.jpeg "Testing")  
- 可用<img />改变属性  

  <img src="https://pic.17qq.com/uploads/gqskpsqmqy.jpeg" alt="A" title="B" width="50" height="50" />

---
### 8.水平线
***
---
___

### 9. 链接
[显示名字](网站地址 "title")

<A@emal.com>  
<https://www.google.com>

**\*注意加https://**

- 引用的reference  
[显示名字][1]
[1]: <https://www.google.com> "title"

- HTML链接显示  
<a href="https://www.google.com" title="title">显示名字</a>

---
### 10. 公式和流程图
行内$\Gamma(n)= (n-1)!\quad\forall n\in\mathbb N$  
$$ x= \dfrac{-b \pm \sqrt{b^2-4ac}}[2a] $$

flow
st=>start: Start
op=>operation: Your Operation
cond=>condition: Yes or No?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op


### 11.参考资料
Markdown入门有这一篇就够了：<https://www.jianshu.com/p/c6aa2f35d5ae>
Markdown 入门参考: <https://xianbai.me/learn-md/index.html>
Markdown数学公式语法：<https://www.jianshu.com/p/e74eb43960a1>
用markdown来画流程图:<https://www.jianshu.com/p/02a5a1bf1096>
