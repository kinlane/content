---
layout: post
title: 'Documents as Cloud Printing Objects'
---
I know very little about the <a href="http://www.kinlane.com/category/publishing/">Print</a> industry.  As I'm learning I find myself applying my programming and IT background to everything.
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" />
Currently I'm prototyping a <a href="http://www.kinlane.com/category/cloud-computing/cloud-print/">Cloud Print</a> platform that provides 2 step commercial <a href="http://www.kinlane.com/category/publishing/">Printing</a> service from top cloud service providers:
<ul class="mainlist">
	<li><a href="http://www.scribd.com/">Scribd</a></li>
	<li><a href="http://issuu.com/">Issuu</a></li>
	<li><a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a></li>
	<li><a href="http://www.kinlane.com/category/google/google-docs/">Google Docs</a></li>
	<li><a href="http://www.box.net">Box.net</a></li>
	<li><a href="http://www.dropbox.com/">Dropbox</a></li>
</ul>
When a user comes from one of these cloud providers or provides a link to their document on the <a href="http://www.kinlane.com/category/cloud-computing/cloud-storage/">Cloud Storage</a> platform they are bringing their content with them.<p></p>
I need a print object to apply to that content and create a printable document.  So I am created 12 separate documents or cloud print objects to deliver common print properties such as binding, size and color.
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo/book-open-pages.jpg" alt="" width="250" align="right" />
Each cloud print object contains the properties most people who are printing from cloud platforms are looking for:
<ul class="mainlist">
	<li>Magazine Style Binding (Saddle Stitch)</li>
	<li>Book Style Binding (Perfect Bound)</li>
	<li>Reporting Style Binding (Spiral Binding)</li>
	<li>8.5 X 11 Print Size (Letter)</li>
	<li>5 X 8 Print Size (A5)</li>
	<li>Color or Black and White</li>
</ul>
I'm enjoying defining these different objects for use in cloud printing.  These are my basic bound document definitions, I will be defining more single sheet, flyer and large format cloud print objects like posters next.