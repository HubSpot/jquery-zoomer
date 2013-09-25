## What is jQuery Zoomer?

jQuery Zoomer is a library which lets you zoom up your iframes using CSS transforms.

### Browser support

Tested and working: Chrome, FF3.6+, IE8+

### Usage

````javascript
$('iframe.zoomer').zoomer({
    zoom: 0.5,
    width: 200
});
````
(Note: this example has already been run on the iFrame below.)

### Demo

<div>
<p>Click the iFrame to open the URL in a separate browser window/tab.</p>
<style>
iframe {
border: 0px;
}
.zoomer-wrapper {
border: 1px solid #aaa;
}
</style>
<iframe class="demo" src="docs/iframe.html"></iframe>
<script src="http://github.hubspot.com/jquery-zoomer/jquery.zoomer.js"></script>
<script src="http://github.hubspot.com/jquery-zoomer/docs/demo.js"></script>
</div>

Once a Zoomer has already been zoomed, you can adjust the zoom amount by later calling:

```javascript
zoom = 0.25; // Change me to any number 0–1 and then hit "Run"

$iframe = $('iframe.demo');
$iframe.data().zoomer.zoom = zoom;
$iframe.zoomer('refresh');
```

### Full Reference

For a full reference, see our [API documentation](http://github.hubspot.com/jquery-zoomer/api/options).