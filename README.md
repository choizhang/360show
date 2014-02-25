#360Show
360度的展示产品，适用于PC和触屏。是对dopelessRotate插件的一个demo展示和部分使用说明。

##demo
这里是一个汽车展示的[demo](http://choi.sinaapp.com/static/360/index.html)

##说明
* [官网说明](http://www.dopeless-design.de/dopeless-rotate-jquery-plugin-360-degrees-product-viewer.html)
* 使用后的一些注意点。
    * 图片名称有一定要求，必需类似0001.jpg,0002.jpg这样的4位数字。
    * 原插件在图片加载完成前用php做了一个loading效果，如果你不想用php脚本，可以在参数里面添加'nophp': true,'nophpimglist': 'images/01/0001.jpg, images/01/0002.jpg'，nophpimglist里面把所有需要的图片放进去。
    * 'reverse': true是控制旋转的方向
    * 他有将单张图片放大显示和在图片上添加链接或文本的说明的功能，不过目前还没用到。

##Contact
If you have any questions or suggestions that don't fit GitHub, send them to [@choizhang](https://github.com/choizhang)