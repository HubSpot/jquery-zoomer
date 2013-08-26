## API Documentation

### Options

<table class="hs-table">
<tr>
<th width="35%">Name</th>
<th>Default [Description]</th>
</tr>
<tbody>
<tr><td>width</td> <td><code>'auto'</code></td></tr>
<tr><td>height</td> <td><code>'auto'</code></td></tr>
<tr><td>zoom</td> <td><code>0.4</code></td></tr>
<tr><td>tranformOrigin</td> <td><code>'0 0'</code><br/></td></tr>
<tr><td>loadingType</td> <td><code>'message'</code><br/>Other option: <code>'spinner'</code></td></tr>
<tr><td>loadingMessage</td> <td><code>'Generating preview...'</code><br/>Message displayed while the iFrame is loading</td></tr>
<tr><td>spinnerURL</td> <td><code>'http://oi46.tinypic.com/6y375z.jpg'</code><br/>Requires <code>loadingType: 'spinner'</code></td></tr>
<tr><td>message</td> <td><code>'Open Page'</code><br/>The text displayed on hover</td></tr>
<tr><td>ieMessageButtonClass</td> <td><code>'btn btn-secondary'</code><br/>Class name added to the Open Page button in IE</td></tr>
<tr><td>messageURL</td> <td><code>false</code><br/>Use a different URL on click then the <code>src</code> of the iFrame</td></tr>
<tr><td>onComplete</td> <td><code>function($iframe) {}</code><br/>Callback function after the iFrame has loaded and been zoomed</td></tr>
</tbody>
</table>

### Methods

<table class="hs-table">
<tr>
<th width="50%">Name</th>
<th>Description</th>
</tr>
<tbody>
<tr><td>$iframe.zoomer('fadeIn')</td> <td>Fades out the loading message to reveal the iFrame beneath.</td></tr>
<tr><td>$iframe.zoomer('fadeOut')</td> <td>Fades in the loading message to hide the iFrame beneath.</td></tr>
<tr><td>$iframe.zoomer('src', newSrc)</td> <td>Changes the src of the iFrame seamlessly. (Fades in the loading message, sets the iFrame src to <code>newSrc</code> and then fades out the loading message after the iFrame finishes loading and gets zoomed.)</td></tr>
<tr><td>$iframe.zoomer('refresh')</td> <td>Alias to calling <code>$iframe.zoomer('src', currentSrc)</code> </td></tr>
<tr><td>$iframe.zoomer('zoomedBodyHeight')</td> <td>Returns the height of the iFrame in zoomed space. (Example: if iFrame contents have height of <code>800px</code> and zoom is set to <code>0.5</code>, returns <code>400</code>.)</td></tr>
</tbody>
</table>