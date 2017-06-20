---
layout: post
title: 'Flipbook Preview for PDF Print Files'
---
When I am building a user interface for any print application I want to allow users to preview their PDF after upload.  The Mimeo Proofing Service is what I use.
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/flipbook.jpg" alt="" width="225" align="right" />
Proofing takes a PDF and generates a small and large image for each page of the PDF, and adds to your Mimeo account.<p></p>
First I pull the PDF, and send it to the Mimeo Proofing Service, and it returns XML containing a list of all the proofed images<span> for PDF.</span><p></p>
I created a PHP script that allows you to <a href="http://nimbus2.laneworks.net/functions-jquery-flipbook-preview.php" target="_blank">preview a PDF you are about to print in a flipbook format</a>.  I use the very simple<a href="http://www.coastworx.com/bookflip.php" target="_blank">Flipbook script from Coast Works</a>.<p></p>
I will be creating a smaller preview version, and probably throw it in some sort of JQuery Lightbox so it can load from the build print document interface.<p></p>
You can download the first version of the flip book as:
<ul class="mainlist">
	<li><strong>git @ github</strong> - <a href="https://github.com/mimeoconnect/mimeo-proof-flipbook" target="_blank">Flipbook Print Proof Preview</a></li>
	<li><strong>svn @ Google Code -</strong> <a href="http://code.google.com/p/mimeo-proof-flipbook/" target="_blank">Flipbook Print Proof Preview</a></li>
</ul>
