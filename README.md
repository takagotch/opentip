### opentip
---
https://github.com/enyo/opentip

```
ender build opentip
bower install opentip 
```

```js
$('elementId').opentip('Content', { showOn: "click", ...option... });

new Opentip("#my-element", "Show after 2 seconds", { delay: 2 });
$("#my-element").opentip("Shown after 2 seconds", { delay: 2 });

```

```
<div data-ot="Tooltip content" data-ot-show-on="click">Click me</div>
```

