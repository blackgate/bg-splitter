# Angular pane splitter

Simple pane splitter for angular.js 

## Sample

HTML:
```html
<bg-splitter orientation="horizontal">
	<bg-pane min-size="100">Pane 1</bg-pane>
	<bg-pane min-size="150">
	  <bg-splitter orientation="vertical">
	    <bg-pane min-size="50">Pane 2</bg-pane>
	    <bg-pane min-size="50">Pane 3</bg-pane>
	  </bg-splitter>
	</bg-pane>
</bg-splitter>
```

Javascript:
```javascript
var app = angular.module('myApp', ['bgDirectives']);
```

## Install using bower

```
bower install bg-splitter
```
