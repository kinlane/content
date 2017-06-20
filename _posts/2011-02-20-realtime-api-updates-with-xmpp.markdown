---
layout: post
title: 'Real-Time API Updates with XMPP'
---
<a href="http://xmpp.org/" target="_blank"><img src="http://kinlane-productions.s3.amazonaws.com/xmpp_logo.png" alt="" align="right" /></a>I'm working on my prototype for a <a href="http://www.kinlane.com/category/google/">Google</a> cloud printer that runs on a server.<p></p>
To set the stage, I want to get cloud print jobs sent from <a href="http://www.kinlane.com/category/google/google-docs/">Google Docs</a> using the <a href="http://code.google.com/apis/cloudprint/docs/overview.html" target="_blank">Google Cloud Print Services Interface</a>.<p></p>
You can retrieve a print job from the Google Cloud Print Services interface using /fetch.<p></p>
All it takes to get a new job is making a call to the Google Cloud Print (GCP) <a href="http://www.apievangelist.com/">API</a> on a regular schedule.<p></p>
The problem with this method is that it isn't real-time, is it? Even if you poll the GCP API every minute...it isn't real-time.<p></p>
To make it real time Google uses a separate <a class="zem_slink" title="Extensible Messaging and Presence Protocol" rel="wikipedia" href="http://en.wikipedia.org/wiki/Extensible_Messaging_and_Presence_Protocol">XMPP</a> connection for sending print notifications to cloud printers.<p></p>
Each cloud printer has to register with the service and get a ClientLogin token, then establish a perseistent connection with the GTalk server to receive updates.<p></p>
With a cloud printer authenticated, and a persisistent <a href="http://xmpp.org/" target="_blank">XMPP</a> connection established a cloud print server can then wait for print job notifications.<p></p>
Two benefits from this method:<img src="http://kinlane-productions.s3.amazonaws.com/real-time.jpg" alt="" width="200" align="right" />
<ol class="mainlist">
	<li><strong>Real-Time -</strong> XMPP makes the GCP API requests truly real-time. As the print job comes in, an XMPP message is sent outnotifyingthe cloud printer.</li>
	<li><strong>Resources -</strong> This is a much more efficient usage of network and compute resources. Cloud Printers only poll the GCP API /fetch end point when it receives job update.</li>
</ol>
As I'm working with the GCP API and building the XMPP notification system I start thinking about this outside of print and the Google Cloud Print API.<p></p>
XMPP notifications is a great way to make APIs truly real-time, as well as reduce the request load on an API. It reduces the need to constantly poll an API for updates.<p></p>
Think if <a href="http://www.kinlane.com/category/twitter/">Twitter</a> provided <a href="http://www.kinlane.com/category/xmpp/" target="_blank">XMPP</a> updates for applications looking for search updates. They would getnotifiedto make an API request when there is truly an update.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/01/printing-with-google-cloud-print-and-xmpp/">Printing with Google Cloud Print and XMPP</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://oreilly.com/catalog/0636920010845/">Email, XMPP, and Task Queues in Google AppEngine</a> (oreilly.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/02/2822/">Google Cloud Print - Fetch</a> (kinlane.com)</li>
</ul>
