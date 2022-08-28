# Markdown 
## 字体&内容
*斜体*
**粗体**
***斜粗体***

[百度](https://www.baidu.com)

<https://www.runoob.com>

这个链接用 1 作为网址变量 [Google][1]
这个链接用 runoob 作为网址变量 [Runoob][runoob]
然后在文档的结尾为变量赋值（网址）,换行号隔开就行

[1]: http://www.google.com/
[runoob]: http://www.runoob.com/

**显示图片**
![Spiderman](https://dogefs.s3.ladydaily.com/~/source/wallhaven/small/o3/o3m9l9.jpg)
**缩放**
<img src="https://dogefs.s3.ladydaily.com/~/source/wallhaven/small/o3/o3m9l9.jpg" width="150%">

---

## 标注

~~不重要的删除线~~
<u>带下划线文本</u>  

文末注释[^mark]
[^mark]: 这是一个文末注释

---

## 列表
* name
  1. first name
  2. last name
* age
  > 1-16
  > 17-30
  >>17-25
  >>25-30
  >>>30


|姓名 （左对齐）|年龄 （右对齐）|*学历 （居中对齐）*|
|:---|---:|:---:|
|A|120|*小学本科*|

---  

## 代码显示
`printf('hello world')`

    clc;
    clear;
    *一个Tab，或者4个空格就可以代码显示一行*


```c 
*指定代码类型，也可省略，反引号在键盘左上角*
#include<iostream>
using namespace std；
void main{
cout << "Hello, world!" << endl;
return 0;
}
```

```javascript
$(document).ready(function () {
    alert('RUNOOB');
});
```
---

##转义字符
*这是字体变斜*
\*这是原本的星号\*

---

##公式

$f(x)=sin(9x+ \pi /4)$

$$Sum=\lim \sum_{i=1}^{n} \frac{i} {2i+1}$$

$$
f{x} = \int_{-\infty}^\infty
    \hat f\xi\,e^{2 \pi i \xi x}
    \,d\xi
$$

$$
\begin{Bmatrix}
   a & b \\
   c & d
\end{Bmatrix}
$$
$$
\begin{CD}
   A @>a>> B \\
@VbVV @AAcA \\
   C @= D
\end{CD}
$$