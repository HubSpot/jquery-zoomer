<h2>What is jQuery Zoomer?</h2>

<p>jQuery Zoomer is a library which lets you zoom up your iframes using CSS transforms.</p>

<h3>Browser support</h3>

<p>Tested and working: Chrome, FF3.6+, IE8+</p>

<h3>Usage</h3>

````javascript
$('iframe').zoomer({ width: 200, zoom: 0.5 });
````

<h3>Demo</h3>

<div>
<p>Click <a href="javascript: $('iframe').contents().find('.demo-container').append('<h4>Inserted text</h4>'); void(0);">here</a> to insert text into the iFrame.</p>
<style>
iframe {
border: 0px;
}
.zoomer-wrapper {
border: 1px solid #aaa;
box-shadow: 0px 1px 8px rgba(0, 0, 0, 0.2);
-webkit-box-shadow: 0px 1px 8px rgba(0, 0, 0, 0.2);
-moz-box-shadow: 0px 1px 8px rgba(0, 0, 0, 0.2);
-ms-box-shadow: 0px 1px 8px rgba(0, 0, 0, 0.2);
-o-box-shadow: 0px 1px 8px rgba(0, 0, 0, 0.2);
}
</style>
<iframe src="iframe.html"></iframe>
<script src="http://github.hubspot.com/jquery-zoomer/jquery.zoomer.js"></script>
<script src="http://github.hubspot.com/jquery-zoomer/docs/demo.js"></script>
</div>

<h3>Full Reference</h3>

For a full reference, see our <a href>API documentation</a>.
