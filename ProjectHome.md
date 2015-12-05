jquery plugin
wish wall, stickies, memo
许愿墙

支持 support IE 6+, Safari 4+, Firefox 3+

使用 Usage:
`$('#OBJ').wish()`;

代码格式 Markup:
`<div id="OBJ">`
> `<div>`1. text`</div>`
> `<div>`2. text`</div>`
> ...
`</div>`

附加：
如需拖动，载入jQuery UI后，添加如下代码
`$('.wish').draggable({containment: "#wish", scroll: false})`;

.wish 为内定class名
#wish 为自定义容器