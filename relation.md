# 关系

页面上的元素之间存在某种关系，我们来理解一下。

## 父与子

如果说用一组元素包装了另一组元素，这就意味着在这两组元素之间创建了某种父与子的关系。包装元素通常叫父元素（parent），被包装的元素叫子元素（child）。

例：

```
<div>
  <h1>无题</h1>
</div>
```

在上面的例子里，我们可以说这个 `<div>` 元素是 `<h1>` 的父元素，这个 `<h1>` 元素是这个 `<div>` 元素的子元素。

## 兄弟

元素之间的兄弟关系。

例：

```
<div class="container">
  <div class="card">
  </div>

  <div class="card">
  </div>
</div>
```

一个带 .container 类的 `<div>` 元素，包装了两个带 .card 类的 `<div>` 元素。这两个带 .card 类的 `<div>` 元素，它们之间的关系就是兄弟，因为它们有一个共同的爸爸，就是带 .container 类的 `<div>` 元素。

例：

```
<div class="container">
  <div class="card">
    <div class="image">
      <img src="images/got.jpg" alt="got">
    </div>
    <div class="content">
      <h2 class="header">权力的游戏</h2>
    </div>
  </div>
  <div class="card">
    <div class="image">
      <img src="images/fargo.jpg" alt="fargo">
    </div>
    <div class="content">
      <h2 class="header">冰血暴</h2>
    </div>
  </div>
</div>
```

两个 .card 是 .container 的子元素，这两个 .card 元素是兄弟关系，每个 .card 里直接包装了 .image 与 .conent ，所以说 .card 是它们的父元素，.image 与 .content 是包装它们的 .card 元素的子元素。在 .card 元素里，我们可以说 .image 与 .content 它们之间是兄弟关系。

