---
layout: post
title: 'View a PDF in the Browser using JavaScript'
---
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/PDF_red.jpg" alt="" width="100" align="right" /><p></p>
I was sitting in on a session at the <a title="Oreilly Velocity Conference" href="http://velocityconf.com/velocity2011">O'Reilly Velocity Conference</a> today, by <a title="Chris Blizzard" href="http://en.wikipedia.org/wiki/Christopher_Blizzard">Chris Blizzard</a> of the <a title="Mozilla Foundation" href="http://www.mozilla.org/foundation/">Mozilla Foundation</a>.  Chris talked covered a wide range of topics in his 20 minutes, but one project really caught my attention.<p></p>
It is a<a title="PDF Reader in javascript" href="https://github.com/andreasgal/pdf.js">PDF Reader in JavaScript</a>. The PDF reader(aka pdf.js), is a technology prototype to explore whether the HTML5 platform is complete enough to faithfully and efficiently render the ISO implementation of the Portable Document Format (PDF).<p></p>
Viewing PDF in the browser has always been a pain in the ass for developers, and generally a bad experience for the user.  Firefox has been working on this for a while, out in the open on Github, but only recently started talking about publicly.<p></p>
The project is not complete, they are still working on some features like Type1 fonts, gradients, etc.  Along the way, they have had to add some new interfaces to the HTML5 canvas element, and replicate some difficult features of the <a title="PDF" href="http://www.kinlane.com/category/pdf/">PDF</a> spec in JavaScript.<p></p>
Mozilla's goal is to be using pdf.js to render PDFs "natively", within Firefox, enabling the browser to <a title="view a majority of the PDF's found on the web today" href="http://developer.mimeo.com/index.php">view a majority of the PDF's found on the web today</a>.  Initially pdf.js will be delivered as a Firefox extension, and eventually baking in, and shipping with Firefox.<p></p>
Mozilla is open-sourcing pdf.js, and releasing under a very liberal 3-clause BSD license.  You can <a title="download and get involved at Github" href="https://github.com/andreasgal/pdf.js">download and get involved over at Github</a>.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://andreasgal.com/2011/06/15/pdf-js/">Pdf.js: Rendering PDF with HTML5 and JavaScript</a> (andreasgal.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.i-programmer.info/bookreviews/29-javascript/2610-javascript-the-definitive-guide-6e.html">JavaScript: The Definitive Guide (6e)</a> (i-programmer.info)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.pcworld.com/article/230446/get_them_while_theyre_hot_firefox5_release_candidates_debut.html">Get Them While They're Hot: Firefox 5 Release Candidates Debut</a> (pcworld.com)</li>
</ul>
