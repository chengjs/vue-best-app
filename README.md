# 脚手架安装

```
$ npm install -g goodapp
```

# 搭建项目

### 初始化项目

```
$ goodapp init
```


# vue-best-app

> 以下是对项目有个负责的态度，如果需要某个的则添加进去

### meta 添加，pwd 渐进式

> 用于前端快速开发移动端meta等优质模板，更多>>>

```
<meta name="title" content="搜索引擎标题">
<meta name="keywords" content="关键词1,关键词2,关键词3" />
<meta name="description" content="搜索引擎介绍网站" />
<meta name="spm_prefix" content="333.400">
<!-- 下面在浏览器中显示手机状态栏颜色 -->
<meta name="theme-color" content="#de698c">
....
```


### 初始化样式 normalize.css

> Chrome，Edge，Firefox ESR +，IE 10+，Safari 8+，Opera。需要兼容IE低版本的话，请自行npm下：[官网](http://necolas.github.io/normalize.css/)。为了很多的样式组件能够一次性将默认样式更改(每次都看到很多小)。这里使用的版本是8，

### 是否需要引入 fastclick.js

> 个人不推荐使用，[官网](https://github.com/ftlabs/fastclick)。 [更多...](https://github.com/chengjs/good_cli/issues/1)

- FastClick是不会对PC浏览器添加监听事件
- Android版Chrome 32+浏览器，如果设置viewport meta的值为width=device-width，这种情况下浏览器会马上出发点击事件，不会延迟300毫秒。

```
<meta name="viewport" content="width=device-width, initial-scale=1">
```

- 所有版本的Android Chrome浏览器，如果设置viewport meta的值有user-scalable=no，浏览器也是会马上出发点击事件。
- IE11+浏览器设置了css的属性 touch-action: manipulation，它会在某些标签（a，button等）禁止双击事件，IE10的为-ms-touch-action: manipulation

### 移动端1px解决

> 只提供解决的方法，但是布局思路是自己的：[更多](https://github.com/chengjs/good_cli/issues/2)

### 图片倍图

> retina.js

待更新...















