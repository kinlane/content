---
layout: post
title: 'Google Cloud Print - Register'
---
<a href="http://www.mimeo.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="200" align="right" /></a>Now that we are <a href="http://www.kinlane.com/2011/02/google-cloud-print-client-login/" target="_blank">authenticated with a specific users Google Account</a> using the <a href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html" target="_blank">Google Client Login API</a>, we can start registering a cloud printer.<p></p>
We will register using the GCP /register endpoint:
<ul class="mainlist">
	<li><a href="http://www.google.com/cloudprint/interface/register">http://www.google.com/cloudprint/interface/register</a></li>
</ul>
Here is our code sample for registering using the Zend framework:<p></p>
<script src="https://gist.github.com/813945.js?file=GCP%20-%20Register"></script> The Google Cloud Print /register endpoint accepts the following parameters:<p></p>
<ul class="mainlist">
	<li><strong>printer</strong> - User readable name of the printer being registered (need not be unique).</li>
	<li><strong>proxy</strong> - Identification of the printer client or proxy (must be unique).</li>
	<li><strong>capabilities</strong> - Printer capabilities (XPS or PPD).</li>
	<li><strong>defaults</strong> - Printer default settings (XPS or PPD).</li>
	<li><strong>status</strong> - Status string of the printere.g., Out of Paper, Online, etc.</li>
	<li><strong>description</strong> - Descriptive string about the printer.</li>
	<li><strong>capsHash</strong> - A hash or digest value of the capabilities data. This value is useful, for example, to compare values and check whether the local printer's capabilities have changed.</li>
</ul><p></p>
I am using the <a href="http://en.wikipedia.org/wiki/PostScript_Printer_Description" target="_blank">PPD format for the printer capabilities</a>, in the future I will explore the usage of <a href="http://en.wikipedia.org/wiki/Open_XML_Paper_Specification" target="_blank">XPS</a>.  Here is an example JSON response:
<script src="https://gist.github.com/813950.js?file=GCP%20-%20Register%20-%20JSON"></script>You now have the cloud printer ID for your registered <a href="http://www.google.com/chrome/intl/en/p/cloudprint.html" target="_blank">Google Cloud Printer</a>.  Users can add the printer as a <a href="http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html" target="_blank">Google Cloud Printer Proxy</a> and send print jobs to it.<p></p>
With the printer ID of your new Google Cloud Printer you can manage the printers status, capabilities, and print jobs from users.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/02/introduction-to-the-google-cloud-print-services-interface/">Introduction to the Google Cloud Print Services Interface</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.macworld.com/article/157364/2011/01/cloudprint.html?lsrc=rss_main">Google Cloud Print lets you print GMail content from your mobile device</a> (macworld.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://thenextweb.com/google/2010/11/02/google-to-offer-cloud-printing-for-chrome-os-web-apps-predicts-cloud-aware-printers/">Google to offer cloud printing for Chrome OS, web apps - predicts "cloud-aware" printers [TNW Google]</a> (thenextweb.com)</li>
</ul>
