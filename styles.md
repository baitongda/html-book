# 样式

页面会用到一些样式，这些样式可以放在样式表里，后面学习 CSS 的时候，我们再详细了解怎么样为页面添加样式。这里先去创建一个样式表，然后把它链接到页面上使用。页面上用的样式表一般放在文档的 head 部分，链接样式用的是 link：

```
<link rel="stylesheet" href="样式表的路径">
```

link 的 rel 属性的值设置成了 stylesheet，表示这是一个样式表。href 属性的值是这个样式表的位置。

## 练习

创建一个样式文件，放在项目下的 styles 目录里面，样式表的名字是 main.css，然后打开 index.html 这个文档，在 head 标签里，链接使用这个样式表：

```
<head>
  <meta charset="UTF-8">
  <title>Document</title>
  <link rel="stylesheet" href="styles/main.css">
</head>
```



