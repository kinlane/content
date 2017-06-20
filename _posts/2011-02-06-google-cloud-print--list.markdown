---
layout: post
title: 'Google Cloud Print - List'
---
<a href="http://www.mimeo.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="200" align="right" /></a>In addition to <a href="http://www.kinlane.com/2011/02/google-cloud-print-register/" target="_blank">registering a Google Cloud Printer</a> you may want to list what cloud printers you have registered with a specific Google Account.<p></p>
After authenticating using <a href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html" target="_blank">Google ClientLogin API</a>,  you can request a list of your printers in their account:<p></p>
<script src="https://gist.github.com/813970.js?file=GCP%20-%20LIST%20"></script> The Google Cloud Print  /list endpoint accepts the following parameter:<p></p>
<ul class="mainlist">
	<li><strong>proxy</strong> - Identification of the proxy, as submitted while registering the printer.</li>
</ul><p></p>
Here is an example JSON response:
<script src="https://gist.github.com/813975.js?file=GCP%20-%20LIST%20-%20JSON"></script>You can store the list of cloud printers in a database and / or display for the user to navigate and manage their Google Cloud Printers.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://www.makeuseof.com/tag/print-phone-gmail-mobile-google-cloud-print/">How To Print From Your Phone With Gmail For Mobile &amp; Google Cloud Print</a> (makeuseof.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/02/introduction-to-google-cloud-print/">Introduction to Google Cloud Print</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://googlesystem.blogspot.com/2011/01/gmail-cloud-print.html">Gmail Cloud Print</a> (googlesystem.blogspot.com)</li>
</ul>
