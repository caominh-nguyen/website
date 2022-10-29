Massively by HTML5 UP
html5up.net | @ajlkn
Free for personal and commercial use under the CCA 3.0 license (html5up.net/license)


This is Massively, a text-heavy, article-oriented design built around a huge background
image (with a new parallax implementation I'm testing) and scroll effects (powered by
Scrollex). A *slight* departure from all the one-pagers I've been doing lately, but one
that fulfills a few user requests and makes use of some new techniques I've been wanting
to try out. Enjoy it :)

Demo images* courtesy of Unsplash, a radtastic collection of CC0 (public domain) images
you can use for pretty much whatever.

(* = not included)

AJ
aj@lkn.io | @ajlkn


Credits:

	Demo Images:
		Unsplash (unsplash.com)

	Icons:
		Font Awesome (fontawesome.io)

	Other:
		jQuery (jquery.com)
		Scrollex (github.com/ajlkn/jquery.scrollex)
		Responsive Tools (github.com/ajlkn/responsive-tools)

Edits by Cao Minh from the original source codes:
Add responsive YouTube frame:
	HTML codes:
		<div class="video-container">
  			<iframe src="https://www.youtube.com/embed/...." frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
		</div>
	CSS codes:
		.video-container {
    			overflow: hidden;
   			position: relative;
    			width:100%;
				}
		.video-container::after {
    			padding-top: 56.25%;
    			display: block;
    			content: '';
				}
		.video-container iframe {
    			position: absolute;
    			top: 0;
    			left: 0;
  			width: 100%;
   			height: 100%;
				}
Credit to https://flaviocopes.com/responsive-youtube-videos/
	
