###angular-colorpicker v1.0.1

===========================
####Demo
===========================
[Demo](http://w3cin.com/demo/angular-colorpicker/example/index.html)


一个基于angularJS的颜色选择器(a color picker based on angularJS)，目前具备一下功能：
- **3种模式** 经典模式、自定义选择模式、历史记录
- **支持的颜色格式** 目前仅支持rgba

####Requirements
- **jquery**
- **angular 1.3.x**（use the oneBind(::)）

####Install
> bower install angular-colorpicker

> npm install angular-colorpicker

####Basic Usage
```html
<colorpicker color="color" color-type="rgba"></colorpicker>
var app = angular.module('app',['ui.colorpicker']);
```

#### Options
- **color**  颜色值
- **color-type** 颜色格式

#### Support
`ie9+`  `chrome` `firefox` `safari`

####License
--------
This colopicker plugin is licensed under the MIT license.

Copyright (c) 2016 linjinying