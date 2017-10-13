# 可编辑的元素

> 这个工具不算新奇，只是提供个方便
>
> 之所以写这么多js代码来实现可编辑效果，是因为仅仅设置点击后可编辑失去焦点不可编辑，或者直接设置编辑后，在给元素添加了其他很多功能后，原生态的编辑就不可使用了。

项目预览：https://alny-ac.github.io/edit/index.html

## 安装



下载地址：https://github.com/ALNY-AC/edit/archive/master.zip



## 快速使用

需要导入的文件在dist文件夹下

1. 导入JQuery
2. 导入editle.css和editel.js
3. 给元素添加`.editel`

````html
<span class="editel">加了.editel就变成了可编辑的了</span>
<h1 class="editel">加了.editel就变成了可编辑的了</h1>
<div class="editel">加了.editel就变成了可编辑的了</div>
````

## 自定义

可以自定义css样式中的内边距等值，其他的可以修改的值就等着你自己去发现啦~~

## 注意

JQuery UI拖动等功能会覆盖编辑效果，而且如果有其他的组件在独占或堵塞焦点状态，编辑功能会无效。
