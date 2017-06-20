---
layout: post
title: 'Dropbox Launches API'
---
<a href="http://kinlane-productions.s3.amazonaws.com/cloud-computing/DropBox-Developers.PNG" target="_blank"><img class="alignnone" style="padding: 15px;" title="Dropbox" src="http://kinlane-productions.s3.amazonaws.com/cloud-computing/DropBox-Developers.PNG" alt="" width="250" height="97" align="right" />Dropbox just launched a new application programming interface (API)</a> for their popular cloud storage platform. The <a href="http://en.wikipedia.org/wiki/Representational_State_Transfer" target="_blank">RESTful API</a> allows you to exchange, distribute or access files on a user's desktop.<p></p>
The API offers the following features:
<ul class="mainlist">
	<li>Simple HTTP+JSON method of accessing a user's information in a user approved sandbox on the user's desktop. List, upload, delete, move, copy, and get files as well as many other features.</li>
	<li> A full event callback API allowing you to get simple asynchronous events to your web site or service whenever the user changes their sandbox. The events are designed to be tight and fast and easy to handle if you can receive HTTP requests and parse JSON.</li>
	<li>Implementations in Java, Ruby, Python, and Objective-C that are being actively used, and all MIT licensed.</li>
</ul>
You can tell their API deployment is fully baked and offers a complete set of support tools:
<ul class="mainlist">
	<li>Overview of the API</li>
	<li>Quick Start</li>
	<li>Announcement Area</li>
	<li>My Applications</li>
	<li>Mobile Documentation</li>
	<li>Client Libraries</li>
	<li>Bug Report</li>
</ul>
It is a well done implementation of a cloud storage API. I will review in more detail and compare against other popular standards like <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a>, <a href="http://www.kinlane.com/category/google/google-storage-for-developers/">Google Storage for Developers</a>, and see how close it is to being a quality <a href="http://www.kinlane.com/2010/06/cloud-storage-api-standard/">standard for a cloud storage API</a>.