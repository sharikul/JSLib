<h1>JSLib documentation is currently undergoing construction.</h1>
<p>In the mean time, read a little about JSLib.</p>
<p>
	
	<em>JSLib</em> is a real lightweight JavaScript library that wants to help you write normal JavaScript in normal JavaScript, in the sense that the code that you write, that will be powered by the JSLib Library in the background, will look a bit like normal JavaScript. JSLib doesn't make use of any symbols in its functions - just characters! Here's a demo:
</p>
<pre>
	// Add the .ready event handler
	document.ready(function() {
	// Make event handlers look built into JavaScript

	var body = document.getTag("body");

	// Style the body using the .addCSS method

	body.addCSS({
	"font-family":"sans-serif",
	"font-size":"20px"
	});
	});
</pre>

<p>If you've used jQuery before, which I presume you have, you'll notice that JSLib resembles it in a way. That's because it has been inspired by the jQuery Library!</p>