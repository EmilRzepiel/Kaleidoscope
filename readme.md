Kaleidoscope 1.0.0 
------------------
Simple, lightweight CSS Framework (minified to 5kb)
by Emil Brann 
(team Poland)



Kaleidoscope speeds up the development of new HTML5 projects. It's simply a .css file (there's actually few to choose from) that does the whole dirty job for you: 
* cleans things up for cross-browser compatibility
* builds the (nestable) grid to keep everything nicely together
* keeps vertical rhythm of your project and 
* adds commonly used classes with Object Oriented CSS in mind

It's been made from the best bits of common practice around the web and altered for even better usage.



Core elements
------------------

* Reset - latest Eric Meyer's reset, altered for even more convenient use
* The Grid - nestable, responsive, box-model based
* Vertical rhythm - keeps vertical rhythm of your project, just choose the font size
* Reusable CSS classess (oocss) - most commonly used classes, plus some more



It comes in 6 flavours
------------------

* ini.css - reset + the grid + reusable classes

  Other files contain all of the above plus:
* ini-12.css - font size 12, baseline 18 set 
* ini-13.css - font size 13, baseline 18 set 
* ini-14.css - font size 14, baseline 20 set 
* ini-16.css - font size 16, baseline 24 set 
* ini-18.css - font size 18, baseline 27 set 

Even better: Try minified version of each file to improve page load speed. 



Implement in no time
------------------

This is a typical structure you use developing websites with Kaleidoscope:

.wrapper {
	
	.row {
		.col-1of2 {
			h1
				header
			p
				lorem ipsum
		}
		.col-1of2 {
			h1
				header
			p
				lorem ipsum
		}
	}

}



Try it out!
------------------

Simply put this line as your first CSS file: 
<link rel="stylesheet" type="text/css" href="http://www.viccolla.com/kaleidoscope/ini-16.css" media="all">

then use this markup:

<div class="wrapper">
	<div class="row">
		<div class="col-1of2">
			<h3>H3 title #1</h3>
			<p>
				Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
				quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo. 
			</p>
		</div>
		<div class="col-1of2">
			<h3>H3 title #2</h3>
			<p>
				Duis aute irure dolor in reprehenderit in voluptate velit esse
				cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
				proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
			</p>
		</div>
	</div>
</div>

and watch what happens.

Don't forget to check out the demo.html file to watch it in action. Also browse through the .css file to learn about everything it contains.



Compatibility
------------------
* IE8+
* All the modern browsers



Thanks
Emil Brann 
http://www.viccolla.com

PS: Thoughts? Suggestions? Wanna say "hi"? emil@viccolla.com