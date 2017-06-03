# class

class 是用在 HTML 标签上的一个属性，在 HTML 语境下，class 表示分类或类别。使用这个属性主要是为了给同类别的元素应用样式。class 属性可以有多个值，每个值中间用空格分隔开，也就是你可以为一个元素添加多个类别。表示类名的时候经常会在名字前面加上一个点（例：.button，.card，.container），因为在 CSS 里，就是用的这种形式表示类。

## 基本用法

```html
<标签名 class="类别-1 类别-2 类别-3...">
```

例 1：

```html
<button class="button">按钮</button>
```

一个按钮元素，上面有个 .button 类。

例 2：

```html
<button class="big red button">按钮</button>
```

一个按钮元素，上面用了 .big，.red，.button 这三个类。

## 练习

1，打开 index.html，添加两行 HTML：

```html
<button class="button">取消</button>
<button class="button">确认</button>
```

上面用了两个按钮元素，元素上的 class 属性设置了类别，它们各自都有一个 .button 类。这样我们就可以在样式表里用到这个类去为元素添加样式，也可以在脚本里面用到这个类，去为元素添加一些行为。

保存文档，在浏览器上观察页面上出现的这两个按钮的样式。

2，打开 styles/main.css，为按钮元素上用的 .button 这个类添加点样式：

```css
.button {
  border: none;
  padding: 4px 16px;
  background: #e0e1e2;
}
```



