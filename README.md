# swiper.rotatefix.js

H5强制横屏页面，通常对页面进行`transform:rotate(90)`，如果页面中使用了`swiper`，会造成`swiper`的滑动方向没有切换过来。

`swiper.rotatefix.js`针对此问题，对`swiper-3.4.2`进行修改，增加了`touchDirectionChanged`参数, 布尔型，默认值是`false`, 如果屏幕进行了`rotate`旋转，需要将此参数设置成`true`, 否则设置成`false`。

希望对此有需求的开发者有所帮助。

swiper相关的css及其它插件请移步至官网
