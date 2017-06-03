# 路径

页面上会用到一些外部资源，比如样式表，脚本，图像，音频，视频等等。链接这些资源的时候，要注意资源的路径，可以使用绝对路径，也可以使用相对路径。

举例说明，比如我们的项目里有这些东西：

```
.
├── index.html
├── images
│   └── hulk.jpg
└── styles
    └── main.css
```

一个 index.html 文档，images 目录下有个 hulk.jpg 图像，styles 目录下有个 main.css 样式表。

## 相对路径

相对路径一般指的是相对于当前这个文档来说，资源所在的路径。如果我们要在项目的 index.html 文档里，使用 hulk.jpg 还有 main.css 资源。使用相对路径的话，这两个资源的路径应该是：

```
images/hulk.jpg
styles/main.css
```

## 绝对路径

资源的绝对路径里一般包含 http 或 https 协议，还有网站的主机名。比如我们的项目在服务器上的地址是 `https://html.ninghao.net`，也就是访问这个地址的时候打开的就是项目下面的 index.html，这样如果在 index.html 里面，要使用 hulk.jpg 与 main.css 的时候，这两个资源的绝对地址应该是：

```
https://html.ninghao.net/imageshulk.jpg
https://html.ninghao.net/styles/main.css
```



