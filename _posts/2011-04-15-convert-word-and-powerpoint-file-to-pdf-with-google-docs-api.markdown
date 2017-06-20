---
layout: post
title: 'Convert Word and Powerpoint File to PDF with Google Docs API'
---
I'm slowly packaging up all the code I've been writing lately for <a title="Google Docs Listing API" href="http://code.google.com/apis/documents/">Google Docs Listing API</a>.<p></p>
I am building quite a few bite size modules that do various things with Google Docs.<p></p>
Today I cleaned up a piece of PHP code that will upload file to Google Docs using API, then export various file types.<p></p>
If it is a .doc file, it will convert to:<img src="http://kinlane-productions.s3.amazonaws.com/word-to-pdf-conversion.gif" alt="" width="200" align="right" />
<ul class="mainlist">
	<li>.pdf</li>
	<li>.png</li>
	<li>.swf</li>
	<li>.txt</li>
	<li>.html</li>
</ul>
If it is a .ppt file, it will convert to:<img src="http://kinlane-productions.s3.amazonaws.com/powerpoint-to-pdf.png" alt="" width="150" align="right" />
<ul class="mainlist">
	<li>.pdf</li>
	<li>.png</li>
	<li>.swf</li>
	<li>.txt</li>
</ul>
This code is a stripped down version of the <a title="Zend - Google Docs API PHP Language Library" href="http://code.google.com/apis/documents/docs/1.0/developers_guide_php.html">Zend - Google Docs API PHP language library</a>, and requires the <a title="Zend GData Library" href="http://framework.zend.com/manual/en/zend.gdata.docs.html">Zend Gdata Library</a> to run.<p></p>
<script src="https://gist.github.com/922855.js?file=Convert%20Word%20and%20Powerpoint%20File%20to%20PDF%20with%20Google%20Docs%20API"></script>