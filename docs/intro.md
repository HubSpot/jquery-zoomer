## What is jQuery Zoomer?

jQuery Zoomer is a library which lets you zoom up your iframes using CSS transforms.

### Browser support

Tested and working: Chrome, FF3.6+, IE8+

### Usage

````javascript
$('iframe.zoomer').zoomer({ width: 200, zoom: 0.5 });
````

### Demo

<div>
<p>Click <a href="javascript: $('iframe').contents().find('.demo-container').append('<h4>Inserted text</h4>'); void(0);">here</a> to insert text into the iFrame.</p>
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

### Full Reference

For a full reference, see our [API documentation](http://github.hubspot.com/jquery-zoomer/api/options).
