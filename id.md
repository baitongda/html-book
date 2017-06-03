# id

id，表示唯一标识符。id 是一个可以在 HTML 标签上用的属性，使用这个属性你可以设置元素的标识符。在一个页面上，元素上不能有重复的标识符，也就是你在 a 元素上用了一个标识符是 main，那在其它的元素上就不能再使用 main 这个名字作为元素的标识符了。

## 基本用法

```html
<元素 id="标识符">
```

例：

```html
<div id="main"></div>
```

## 练习

1，打开 index.html，添加一行 HTML 代码：

```html
<button id="submit">确认</button>
```

2，打开 scripts/main.js，添加两行 JavaScript 代码：

```js
document.getElementById('submit')
  .addEventListener('click', function() {
    console.log('确认 ~ ')
  }, false)
```

上面的 JavaScript 代码，主要就是找到页面上的 id 值是 submit 的这个元素，然后监听元素的点击事件，有人点了这个元素以后，就在控制台上输出一个 “确认 ~”。

保存文档，在浏览器上预览页面，打开浏览器的开发者工具，Console 标签，然后点击页面上的 “确认” 按钮。观察控制台上出现的文字。

