### 1. 绘制爱心
使用js的canvas 2D绘图

javascript canvas 绘图:
https://developer.mozilla.org/zh-CN/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes

公式参考链接:
http://www.360doc.cn/mip/680393802.html
https://wk.baidu.com/view/6296ddd1b14e852458fb574f

公式:
$$
(x^2 + y^2-1)^3=x^2y^3
$$
知x时y的解,公式不会打，直接拿网上的图片

![](README/formula.png)


根据屏幕大小适应canvas宽高:
```js
canvas.width=screen.availHeight;
canvas.height=screen.availHeight;

canvas.width=screen.availHeight>screen.availWidth?screen.availWidth:screen.availHeight;
    canvas.height=canvas.width;
```