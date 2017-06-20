---
layout: post
title: 'Proofing Print Documents From Box.net'
---
I am making my way through each major <a href="http://www.kinlane.com/category/cloud-computing/cloud-storage/">cloud storage</a> provider and building demos that pull PDF files from the provider and proofs the file before <a href="http://www.kinlane.com/category/publishing/">printing</a> with <a href="http://www.mimeo.com">Mimeo</a>.
<a href="http://www.box.net" target="_blank"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/box-net-logo.jpg" alt="" width="200" align="right" /></a>
I have put together a demonstration of how to <a href="http://nimbus2.laneworks.net/functions-pull-pdf-from-box-net-and-prepare-proof.php" target="_blank">pull a PDF file from Box.net and the proof it with Mimeo Connect</a>.<p></p>
You will need:
<ul class="mainlist">
	<li><a href="http://www.box.net" target="_blank">Box.net Account</a></li>
	<li><a href="http://www.mimeo.com/" target="_blank">Mimeo API Account.</a></li>
</ul>
This <a href="http://www.kinlane.com/category/cloud-computing/cloud-print/">Cloud Print</a> demonstration is written in <a href="http://www.kinlane.com/category/php/">PHP</a>, and uses the <a href="https://github.com/mimeoconnect/Mimeo-Connect-Cloud-Print-API---REST-Client" target="_blank">Mimeo Connect Cloud Print API REST Client</a>.
<a href="http://www.mimeo.com" target="_blank"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>
You can download the source code for the Box.netto Mimeo Connect project in the following formats:
<ul class="mainlist">
	<li><a href="https://github.com/mimeoconnect/Mimeo-Box.net" target="_blank">git (GitHub Repository) - Box.net to Mimeo Print</a></li>
	<li><a href="https://code.google.com/p/mimeo-box-net/" target="_blank">svn (Google Code Project - Box.net to Mimeo Print</a></li>
</ul>
I will be updating this project when I develop any new code that integrates Box.net and the Mimeo Connect Cloud Print API.<p></p>
This project currently allows you to pull print files from Box.net and proof them with Mimeo Connect Cloud Print API and preview or view any pages in the PDF as images in Flash or <a href="http://www.kinlane.com/2011/01/jquery-powered-flipbook-for-previewing-print-files/">JQuery Flipbook</a>.
