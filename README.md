从 [哔哩哔哩Windows客户端](https://app.bilibili.com/) 解包得到的2233娘live2D模型

By：@初代目葱娘

---

~~（伪）~~食用方式：

1. 引入`live2d.js`

```html
<script type="text/javascript" src="./live2d.js"></script>
```

2. 放置canvas

```html
<canvas id="live2d" width="220" height="250"></canvas>
```

3. 绑定模型

```js
loadlive2d("live2d", "./model/22/model.default.json");
```

---

示例html代码：

```html
<!DOCTYPE html>
<html>

<head>
    <meta charset="UTF-8" />
    <title>live2d测试</title>
    <script type="text/javascript" src="./live2d.js"></script>
</head>

<body>
    <canvas id="live2d" width="220" height="250"></canvas>
    <script type="text/javascript">loadlive2d("live2d", "./model/22/model.default.json");</script>
</body>

</html>
```
