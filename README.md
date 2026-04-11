## 2233live2d

从 [哔哩哔哩 Windows 客户端](https://app.bilibili.com/) 解包得到的 2233 娘 live2D 模型

---

食用方式：

使用非常简单，只需要如下三步：

1. 引入`live2d.js`

```html
<script type="text/javascript" src="res/js/live2d.js"></script>
```

2. 放置 canvas

```html
<canvas id="live2d" width="512" height="512"></canvas>
```

3. 绑定模型

```js
loadlive2d("live2d", "res/model/22/model.default.json");
```

\* 示例 html 可见`demo.html`
