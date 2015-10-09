#关于drawFlowChart

drawFlowChart是基于[flowchart.js](http://adrai.github.io/flowchart.js/)来生成流程图的项目。使用flowchart.js的流程图生成`SVG`格式的流程图，再使用`canvg`把SVG转换成canvas，最终生成`base64`位格式的图片。

## 对canvg进行了微调

在使用canvg对marker进行绘制箭头时，发现，marker中的`refX`与`refY`属性失效。所以对它进行了修复。（目前2015-10-09 canvg是有这个问题，以后版本应该会被修复）


## 适用浏览器

本项目是在chrome下开发的，其它浏览器没有测试过。估计firefox和ie9以上都是可以运行的


## 感谢

感谢 `flowchart.js` 和 `canvg`。

flowchart.js 的GigHub地址： [http://adrai.github.io/flowchart.js/](http://adrai.github.io/flowchart.js/)

canvg 的GigHub地址: [https://github.com/gabelerner/canvg](https://github.com/gabelerner/canvg)



