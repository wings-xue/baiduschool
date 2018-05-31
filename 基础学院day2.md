## html 语意
元素 + 属性 + 属性值 (+ 文档结构)

元素是一整个标签整理   
```<p>包括内容都属于元素</p>```

### 全局属性 
所有的元素都可以使用的属性
#### id, class
定位
#### title
规定元素的工具提示文本
#### lang
全局属性，内容的语言
```<p lang="fr">Ceci est un paragraphe.</p>```

### 元数据
必须在head里面


#### title   
标题

#### meta

name，http-equiv 属性种类
content 内容
```
<meta name="keywords" content="HTML,ASP,PHP,SQL">
<meta http-equiv="charset" content="iso-8859-1">
<meta http-equiv="expires" content="31 Dec 2008">
```
| name        | description                          |
| ----------- | ------------------------------------ |
| application | 当前页面所属Web应用程序的名称        |
| author      | 当前页的作者的名称                   |
| description | 当前页面的描述                       |
| generator   | 生成HTML的软件的名称                 |
| keywords    | 一组用逗号分隔的字符串，用于描述内容 |


#### link 
```
<link href="default.css" rel="stylesheet" title="Default Style">
<link href="fancy.css" rel="alternate stylesheet" title="Fancy">
<link href="basic.css" rel="alternate stylesheet" title="Basic">
```

### 区块
header footer section h1-h6 nav aside

### 分组内容
p hr pre blockquote
```
<p>His next piece was the aptly named <cite>Sonnet 130</cite>:</p>
<blockquote cite="http://quotes.example.org/s/sonnet130.html">
  <p>My mistress' eyes are nothing like the sun,<br>
  Coral is far more red, than her lips red,<br>
  [...]</p>
</blockquote>
```
main  div

### 文本集语意
|tags|description|
|---|---|
|em |强调， 斜体|
|strong|  强调， 粗体|
|i|画外音|

