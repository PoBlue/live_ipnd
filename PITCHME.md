# Week 2

---

## 目的

这次直播课，你将学到：

- 如何将脑中所想的变成代码
- 兼容不同的浏览器
- 利用 display 属性进行布局

---

## 步骤

1. 画出草稿
2. 写出 HTML 树
3. 变成一份代码

---

## HTML 树 

![Dom tree](https://encrypted-tbn1.gstatic.com/images?q=tbn:ANd9GcTct3PwPsbZ1T72NVjpRZWo-QOtmkeRXHTL9Iww7nVUiDlR5ZROv1VIAhP9)

---

## 思考方式

- 自上向下
- 自下向上

---

## 兼容浏览器

---

### Safari 和 Chrome 的对比

---

如何避免:

- 用 normal.css，覆盖默认的样式(预先知道哪些不同，再覆盖掉
- 添加前缀来兼容实验属性
- 更多

---

## display 属性

---

### block (块元素)

- 尽可能撑满容器
- 例子：div, p

```css
tag {
	display: block
}
```

---

### inline (内联元素）

- 占用 **内容一样** 的宽度
- 例子：span, a, em, img

```css
tag {
	display: inline
}

```

---

### flex

- 设置宽度和高度

```css
tag {
	display: flex
}
```

---

### 利用 display 做简单的布局

- [参考](https://developer.mozilla.org/en-US/docs/Web/CSS/flex)