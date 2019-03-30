# 前端学习

### css
+ background-position:描述左右的词 描述上下的词 (描述背景图片的位置)
+ background-attachment 设置背景图片是否固定
    + fixed 背景会固定，不会被滚动条滚走
    + scroll 会跟随滚动条
+ background 综合属性，可以将多个属性写在一起
    + 示例 background:url(1.jpg) no-repeat 100px 100px fiexd;


### css选择器
#### 1.后代选择器，用空格隔开。后代之间不一定是紧挨在一起的，保持一个后代的关联即可
 示例：
```html
 <style type="text/css">
	.div1 p{
		color:red;
	}
</style>
```
#### 2.交集选择器,用.连接
示例
```css
h3.red{
    color:red;
}
```

#### 3.并集选择器,用，隔开
示例
```css
p,h1,h4, h3.red{
    color:red;
}
```

#### 4.子代选择器
示例,表示div下的直接子元素p
```css
div>p{
    color:red;
}
```

#### 4.下一个兄弟选择器
示例,表示div下面紧跟着的兄弟元素P
```css
div+p{
    color:red;
}
```


### CSS权重
|名称|举例|值|
|---|---|---|
|!important|行尾加入！important|无穷大|
|内联样式|style=""|1000|
|ID|#ID|100|
|class/属性/伪类|.class、a:link|10|
|标签/元素/伪元素|div|1|


## Test
