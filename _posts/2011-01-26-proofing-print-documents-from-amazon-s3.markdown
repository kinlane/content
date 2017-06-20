---
layout: post
title: 'Proofing Print Documents From Amazon S3'
---
I am making my way through each major <a href="http://www.kinlane.com/category/cloud-computing/cloud-storage/">cloud storage</a> provider and building demos that pull PDF files from the provider and proofs the file before <a href="http://www.kinlane.com/category/publishing/">printing</a> with <a href="http://www.mimeo.com">Mimeo</a>.
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />
I have put together a demonstration of how to <a href="http://nimbus2.laneworks.net/functions-pull-pdf-from-amazon-s3-api-and-prepare-proof.php" target="_blank">pull a PDF file from Amazon S3 and the proof it with Mimeo Connect</a>.<p></p>
You will need:
<ul class="mainlist">
	<li><a href="http://aws.amazon.com/" target="_blank">Amazon Web Services Account</a></li>
	<li><a href="http://www.mimeo.com/" target="_blank">Mimeo API Account.</a></li>
</ul>
This <a href="http://www.kinlane.com/category/cloud-computing/cloud-print/">Cloud Print</a> demonstration is written in <a href="http://www.kinlane.com/category/php/">PHP</a>, and uses the <a href="https://github.com/mimeoconnect/Mimeo-Connect-Cloud-Print-API---REST-Client" target="_blank">Mimeo Connect Cloud Print API REST Client</a>.
<a href="http://www.mimeo.com" target="_blank"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>
You can download the source code for the <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a> to Mimeo Connect project in the following formats:
<ul class="mainlist">
	<li><a href="https://github.com/mimeoconnect/mimeo-amazon-s3" target="_blank">git (GitHub Repository) - Amazon S3 to Mimeo Print</a></li>
	<li><a href="https://code.google.com/p/amazon-s3-mimeo/" target="_blank">svn (Google Code Project - Amazon S3 to Mimeo Print</a></li>
</ul>
I will be updating this project when I develop any new code that integrates Amazon S3 and the Mimeo Connect Cloud Print API.<p></p>
This project currently allows you to pull print files from Amazon S3 and proof them with Mimeo Connect Cloud Print API and preview or view any pages in the PDF as images in Flash or <a href="http://www.kinlane.com/2011/01/jquery-powered-flipbook-for-previewing-print-files/">JQuery Flipbook</a>.