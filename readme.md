# canvas-ribbon.js

> 重写了Vue作者博客中的canvas背景彩带，简单一条命令为你的网站加上canvas-ribbon背景动画。
>
> 鼠标每次点击，随机生成彩带背景。

## 1. 使用

在页面中插入以下语句。

```html
<script id="ribbon" src="js/canvas-ribbon.js"></script>
```

**注意**此处要为script标签设置 `id="ribbon"` 。插入位置任意，推荐插入到 `</body>` 标签上面。

## 2. 配置

可自定义背景彩带的宽度、透明度和z-index属性
- **`size`**: 彩带宽度, 默认: **`90`**.
- **`alpha`**: 彩带透明度, 默认: **`0.6`**.
- **`zIndex`**: 彩带html标签的z-index属性, 默认: **`-1`**.

例:

```html
<script id="ribbon" size="150" alpha='0.3' zIndex="-2" src="js/canvas-ribbon.js"></script>
```

**不设置**时为默认属性。
