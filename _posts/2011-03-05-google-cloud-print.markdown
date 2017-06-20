---
layout: post
title: 'Google Cloud Print'
---
<a title="Google Cloud Print" href="http://code.google.com/apis/cloudprint/docs/overview.html">Google Cloud Print</a> provides a printing platform that allow printers to be accessed over the Internet by mobile phone, tables and computers.<p></p>
Google Cloud Print enables printing over the Internet to web enabled printers or older printers using a proxy software that users can installed on Windows, and soon Mac and Linux platforms.<p></p>
Cloud Printing is available in Google Apps like Docs and Gmail, Chrome Browser, and the <a title="Google Chrome OS" href="http://www.google.com/chromeos/index.html">Google Chrome Operating System.</a>
<a href="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/GCP-Overview.png">
<img class="aligncenter" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/GCP-Overview.png" alt="" width="550" />
</a>
Third party software developers can access GCP using an API called the <a title="Google Cloud Print Services Interface" href="http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html">Google Cloud Print (GCP) Services Interface</a>.<p></p>
The GCP API provides access to the following services for cloud printers:
<ul class="mainlist">
	<li><a href="http://www.kinlane.com/2011/02/google-cloud-print-register/" target="_blank">/register</a></li>
	<li><a href="http://www.kinlane.com/2011/02/google-cloud-print-list/" target="_blank">/list</a></li>
	<li><a href="http://www.kinlane.com/2011/02/google-cloud-print-update/" target="_blank">/update</a></li>
	<li><a href="http://www.kinlane.com/2011/02/google-cloud-print-delete/" target="_blank">/delete</a></li>
</ul>
The GCP API provides access to each printers print jobs via the following services:
<ul class="mainlist">
	<li><a href="http://www.kinlane.com/2011/02/2822/" target="_blank">/fetch</a></li>
	<li><a href="http://www.kinlane.com/2011/02/google-cloud-print-control/" target="_blank">/control</a></li>
</ul>
Print job notifications are sent to registered printers using a <a title="Persistent Gtalk / XMPP Connection" href="http://www.kinlane.com/2011/02/google-cloud-print-xmpp-print-job-notifications/">persistent GTalk / XMPP connection</a>.<p></p>
Google Cloud Print Services provides a platform for managing printers and distributing print jobs to any printer over the Internet.<p></p>
Using Google Apps and third party software users will be able to print to to home, office and commercial printers on their mobile, table, laptop and desktop computers.
