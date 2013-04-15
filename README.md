<h1>Write normal JavaScript in normal JavaScript.</h1>
<p>JSLib is a new JavaScript library that wants to help you write JavaScript in such a way without cluttering up your source code.</p>
<p>Rather than writing <code>document.addEventListener("DOMContentLoaded", function() {...}, false)</code> or the jQuery equivalent, <code>$(document).ready(function() {...}</code>, you can simply write <code>document.ready(function() {...}</code> and still get done what you intended to get done.</p>

<p>JSLib doesn't want you to move away from libraries such as jQuery, infact, that's where most of the inspiration for JSLib came from in the first place! When writing JSLib code, you may reminisce about writing jQuery code, if you've done so in the past!</p>

<p>Now, let's meet the functions!</p>
<code>window/document.onload</code> <p>- This function handles events relating to the timeframe in which the document is loading, i.e. files are being downloaded from their respective servers to your web browser. <p><br>
<code>window/document.ready</code> <p>- This function handles events to occur when the document is loaded, i.e. when all files needed to make up a webpage have been downloaded onto your web browser. This is where you may write most of your JavaScript code, just like in jQuery.</p><br>
<code>element.press</code> <p>- This function is an event handler for click events. With that said, it's probably self explanatory.</p><br>
<code>element.html</code> <p>- This function retrieves the HTML code from inside the element and returns it as a string.</p><br>
<code>element.addCSS</code> <p>- Similar to jQuery's <code>css</code> method, this function stylizes the current object linked. You specify different properties in the form of objects, just like how you would do in jQuery if you're supplying multiple properties.</p><br>
<code>element.toggle</code> <p>- This function toggles the linked element, i.e. hides it from view/shows it.</p><br>
<code>element.hover</code> <p>- This function handles all event relating to when the mouse 'hovers' over the linked element.</p>
<br>
<code>leave</code>
<p>- This function handles all events relating to when the mouse cursor moves away from the linked element.</p>
<br>
<code>element.setAttr</code>
<p>-</p>
<br>
