---
layout: post
title: 'Create a Cloud Printer with Box.net'
---
<a href="&quot;http://www.box.net"></a><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/box-net-logo.jpg" alt="" width="250" align="right" />A while back I was playing around with the <a title="Box.net API" href="http://developers.box.net/w/page/12923958/FrontPage">Box.net API</a>, I wanted to see what services they offered.<p></p>
I created a set of <a title="PHP Script for Proofing Box.net Files at Mimeo" href="http://www.kinlane.com/2011/02/proofing-print-documents-from-box-net/">PHP scripts for proofing Box.net files at Mimeo</a> and preparing for printing.<p></p>
At the same time I discovered their <a title="OpenBox Platform" href="http://www.box.net/services">OpenBox platform</a>.  OpenBox allows me to add applications to the Box.net platform and create associated actions with my application.<p></p>
When a user adds an OpenBox application, the actions for that application are available in their Box.net account.<p></p>
Using my Box.net developer account:
<ul class="mainlist">
	<li>I added a new application with Box.net.</li>
	<li>I call my application <em>Cloud Report Printer</em></li>
	<li>I give the application a description and image.</li>
	<li>I add an action called Print Report @ Mimeo with a callback URL to the script I wrote for proofing Box.net files at Mimeo.</li>
</ul>
I can share the URL of my application with users and keep private or publish to directory, either way users can add my Cloud Report Printer to their Box.net account.
<a href="http://www.mimeo.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>
Then when editing a document, they have an action called Print Report @ Mimeo.<p></p>
I've just created a prototype for a cloud printing and publishing application with Box.net<p></p>
I can mix and match different types of documents at Mimeo and create an application at Box.net to print to them at Mimeo.<p></p>
This opens up a lot of possibilities.<p></p>
I will have other cloud printer prototypes that run on <a title="Box.net" href="Box.net">Box.net</a> and print to <a title="Mimeo" href="http://www.Mimeo.com">Mimeo.com</a> in the near future.
