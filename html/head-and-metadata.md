## meta

```html
<meta charset="utf-8">
```
meta有`name`和`content`两个属性，常用：

```html
<meta name="author" content="xxx">
<meta name="keywords" content="a b c">
```

> 其中keywords已被搜索引擎弃用，很多网站写了很多不相关的关键字，误导了搜索引擎。

## link

常用于设置favicon，也就是被设置为favorites或者bookmarks时的图标。

```html
<link rel="favicon" href="/favicon.ico">
```

或者，用于链接外部样式文件：

```html
<link rel="stylesheet" href="/css-file.css">
```

## html

常用属性，就是lang用于设置本网站的语言。

```html
<html lang="en-US">
</html>
```