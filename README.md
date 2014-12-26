test
====
<!DOCTYPE html>
<html lang='en'>
	<head>
		<meta charset="UTF-8"> 
		<title>Explaining HTML</title>
		<link rel="stylesheet" type="text/css" href="stylesheet.css">
	</head>
	<body>
		<header>
		<h1>Explaining HTML</h1>
		</header>
		<h3>Basics:</h3>
		
		<article>
		<p>Specify the DOCTYPE as html, then open the "html" tags, while specifying English 
		as language. Remember to close the "html" tag, as well as "body", "head", and "title", 
		among others.</p>
		
		<p>Comments can be written with the "!--" tag.</p>
		
		<p>All tags go inside the "<>" symbols, and all closing tags have a "/" before the name 
		of the tag.</p>
		</article>
		
		<article>
		<p>Write inside "title" tags to write a title for the tab. The title for this program is 
		"Explaining HTML".</p>
		
		<p>The title is in the "head" tag, and this text is in the "body" tags, within "p" tags 
		for paragraph.</p>
		
		<p>The "br" tags separate lines as would pressing enter.</p>
		</article>
		
		<article>
		<p>Headings, such as the one this page has, can be made using the "h1" through "h6" tags;
		they have decreasing font size as the sub-index increases.</p>
		
		<p>To change the colour and style of the font, CSS is needed.</p>
		
		<p>For images, the "img" tag is used; an address is necessary, "src", as well as "height" and "width" attributes.
		An "alt" attribute is useful as alternate text when the image cannot be displayed.</p>
		</article>
		
		<article>
		<p>Hyperlinks use the "a" tag, which requires defining the variable "href" as the address.
		These can be grouped in a navigation section, "nav". This navigation section can include
		links, "li", to other html,inside an unordered list, "ul".</p>
		
		<p>You can make an image a hyperlink by mixing the "a" and the "img" tags creatively.</p>
		</article>
		
		<section>
		<h4>Example:</h4>
			<img src="images/thinker.jpg" height="200" width="200" alt="oops"><br>
			<p>If you still don't understand, 
			<a href="https://www.youtube.com/watch?v=CGSdK7FI9MY">click here.</a>
			</p>
		</section>
		
		<article>
		<p>Audio can be played using the "audio" tags, as well as a nested "source" tag, with
		a defined variable "src", and optional variable "type". Attributes can be used in the
		"audio" tag to display controls, loop, or autoplay.</p>
		
		<p>Other functions include "article", "aside", "footer", "header", "main", "nav", and "section", used
		to facilitate CSS rendering.(Not really used in this HTML)</p>
		
		<p>You can create buttons with the "button" tag, and "inputs"(Normally used with "click" function in Javascript).</p>
		
		<input id="example" type="text"></input>
		
		<button id="ex">Like this</button>
		</article>
	</body>
</html> 

test
