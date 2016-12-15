用于angular.js的splitter指令

具有如下功能：

* 不需要类似splitter-pane的指令引入pane，div[splitter]的任何直接子元素自动成为pane。
* 可以有多于2个pane。如果pane数为0或1，则splitter不做任何事情。
* 用css的width和min-width管理pane的宽度或高度。
* 可以设置水平和垂直方向，可以混合嵌套使用。
* 可以单击最小化或恢复pane（如果不需要这个功能可以选择splitter-noclick.js)。
* splitter.js(8kb, 180行), splitter-noclick.js(5kb， 130行)
* splitter.min.js(5kb), splitter-noclick.min.js(3.3kb)

https://github.com/chaosim/splitter

安装：bower install splitter