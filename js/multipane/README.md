# splitter directive for angular.js

a simple multiple panes splitter directive for angular.js

to move splitter, just drag or click split handlers.

please use splitter-noclick.js if it's not necessary to click to minimize.

## description
add `<div splitter> ...</div>` to html body for horizontal splitter, and `<div splitter vertical="true"> ...</div>`
for vertical splitter.

splitter.js will set the "position" style of the div[splitter] and all of its direct children(div should be good) to "absolute", and insert
`<div class="horizontal split-handler" style="position:absolute;"></div>` or `<div class="vertical split-handler" style="position:absolute;"></div>` between all of the childrens.

To control the split-handlers and the panes' position and size, splitter.js take the css style(top, left, width, min-width, height, min-height) of div[splitter] and its children .

Please use px as the css style's unit. I'm not sure whether other settings works.

Thanks to  blackgate; I learned how to code this splitter from his project(github.com/blackgate/bg-splitter).

## sample
see horizontal.html, vertical.html, nested.html for samples.

Javascript:
```javascript
var app = angular.module('myApp', ['splitter']);
```

## Install using bower

```
bower install splitter
```
