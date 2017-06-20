---
layout: post
title: 'Internet Explorer 9 - HTML 5 Support'
---
<img class="alignnone" style="padding: 15px;" title="Internet Explorer" src="http://kinlane-productions.s3.amazonaws.com/InternetExplorer.jpg" alt="" width="200" align="right" /><a href="http://ie.microsoft.com/testdrive/info/ReleaseNotes/Default.html" target="_blank">Microsoft recently released some new additions to their Windows Internet Explorer Platform</a>, aka. Internet Explorer 9.<p></p>
They are working hard to support more of the HTML5 standard.<p></p>
<strong>Features Available <span style="color: #0000ff;">(</span></strong><span style="color: #0000ff;">Blue are New Releases)</span>
<ul class="mainlist">
	<li> <span style="color: #0000ff;">Canvas - In the latest Platform Preview we support all Canvas element APIs and most Canvas 2D Context APIs and attributes.</span></li>
	<li><span style="color: #0000ff;">&lt;video&gt; - MP4 H.264 playback support, using hardware or software decoding and support for WebM software is not included in this release</span></li>
	<li><span style="color: #0000ff;">&lt;audio&gt; - MP3 and AAC audio support</span></li>
	<li><span style="color: #0000ff;">window.msPerformance - This API is being worked in partnership with members of the W3C and is subject to change</span></li>
	<li>IE9 User Agent String</li>
	<li>getElementsByClassName</li>
	<li>characterSet</li>
	<li><span style="color: #0000ff;">HTML5-conformant whitespace handling</span></li>
	<li>CSS3
<ul class="mainlist">
	<li>Media Queries</li>
	<li>Selectors (entire module and ::selection)</li>
	<li>Namespaces (all except attribute selectors)</li>
	<li><span style="color: #0000ff;">Backgrounds &amp; Borders</span></li>
	<li>Color (rgba(), opacity)</li>
	<li><span style="color: #0000ff;">Values &amp; Units</span></li>
</ul>
</li>
	<li><span style="color: #0000ff;">Web font formats</span></li>
	<li>HTML5 Events</li>
	<li><span style="color: #0000ff;">DOM Style</span></li>
	<li><span style="color: #0000ff;">DOM Core</span></li>
	<li>DOM Traversal</li>
	<li>DOM Range</li>
	<li>DOM L2 Events (complete)</li>
	<li>DOM L3 Events (complete)</li>
	<li>HTML5 Selection</li>
	<li><span style="color: #0000ff;">XHTML Documents - The XHTML mime-type of application/xhtml+xml is now listed in the Accept header of outgoing requests</span></li>
	<li><span style="color: #0000ff;">Generic XML Improvements (text/xml and application/xml)</span></li>
	<li><span style="color: #0000ff;">Generic XML documents render contained SVG and XHTML content</span></li>
	<li><span style="color: #0000ff;">XSLT via &lt;?xml-stylesheet  ?&gt;</span></li>
	<li>SVG</li>
	<li>ICC v2 and v4 color profiles are supported on images</li>
</ul>
<strong>Features Partially Implemented<span style="color: #0000ff;"> </span></strong><span style="color: #0000ff;"><strong> (</strong>Blue are New  Releases)</span>
<ul class="mainlist">
	<li> <span style="color: #0000ff;">Canvas</span>
<ul class="mainlist">
	<li><span style="color: #0000ff;">globalCompositeOperation - The latest Platform Preview does not include support for the globalCompositeOperation attribute.</span></li>
	<li><span style="color: #0000ff;">DOM Exceptions - The latest Platform Preview does not include support for Canvas 2D Context DOM Exceptions.</span></li>
	<li><span style="color: #0000ff;">drawFocusRing() - The latest Platform Preview does not include support for the drawFocusRing() Focus management API.</span></li>
</ul>
</li>
	<li><span style="color: #0000ff;">CSS3 Fonts - font-size-adjust and advanced font features are not supported</span></li>
	<li>DataURI - Support in script source</li>
</ul>
Looks like they are trying to get up to speed with other browsers in the HTML 5 support game. I will take some time to compare against the HTML core specs to see how they are doing overall.