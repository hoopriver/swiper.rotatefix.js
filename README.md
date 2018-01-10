# swiper.rotatefix.js

H5强制横屏页面，通常对页面进行transform:rotate(90)，如果页面中使用了swiper，会造成swiper的滑动方向没有切换过来。

swiper.rotatefix.js针对此问题，对swiper-3.4.2进行修改，增加了`touchDirectionChanged`参数, 布尔型，默认值是flase, 如果屏幕进行了rotate旋转，需要将此参数设置成true, 否则设置成false。

希望对大家能够提供帮助。
