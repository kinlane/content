---
layout: post
title: 'Google Has a Solid Vision of Cloud Printing'
---
<img src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png" alt="" width="300" align="right" />Google is moving forward with their vision of Cloud Printing in a much larger, comprehensive and decisive way compared with <a title="HP ePrint" href="http://www.kinlane.com/2011/03/hp-eprint-web-connected-printers/">HP ePrint</a> or <a title="Apple Airprint" href="http://www.kinlane.com/2011/03/apple-airprint/">Apple Airprint</a>.<p></p>
They have rolled out the <a title="Google Cloud Print Services Interface" href="http://code.google.com/apis/cloudprint/docs/proxyinterfaces.html">Google Cloud Print Services Interface</a> as well as an XMPP jobs notification system.<p></p>
GCP supports printing on mobile phones using Google Docs and Gmail, while also supporting printing in Chrome on Windows, and now on the Mac Platform.<p></p>
They quickly evolved from a <a title="Google Client Login" href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html">Google Client Login</a> to support <a title="OAuth 2.0" href="http://code.google.com/apis/accounts/docs/OAuth2.html">OAuth 2.0</a>, to keep in line with the rest of the Google API ecosystem when it comes to authentication.<p></p>
They also have a clear stance on an architecture where the printers connect directly to cloud print services versus one where the GCP service connects to your printers via a proxy.<p></p>
Google is strongly recommending that developers and device manufacturers allow users to connect their printers directly to the cloud services and bypass a proxy. Their reasoning for this is:
<ul class="mainlist">
	<li><strong>Simplicity</strong> - Fewer moving parts means easier development and fewer maintenance problems.</li>
	<li><strong>Privacy</strong> - Users are concerned with putting their data in the cloud, and routing through a proxy adds another layer to be concerned about.</li>
	<li><strong>Development Speed</strong> - Developing, scaling, and managing a cloud based print service is costly and time consuming. Enabling printers to work directly with GCP, eliminates a lot of development effort.</li>
</ul>
Many developers are building proxies to offer analytics, operation management, secure printing, green print management and many other features.<p></p>
This can be done without forcing printers to route through a proxy.   If manufacturers build printers to be web-enabled, they can work directly with GCP services.   Then operational and management systems can access users accounts using the GCP services interface.
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="200" align="right" />
This just makes sense.   I get a lot of questions via email, twitter and comments on my site regarding how to diagnose printer problems using Google Cloud Print.<p></p>
The biggest question I get is how users can print when their computers are offline.   I think this is the most obvious aspect that Google is trying to point out with their vision.   If devices are web-enabled and work directly with GCP, it eliminates the need to leave computers on and introducing another point where problems can occur.<p></p>
The goal of Google Cloud Print is empower the user with easy, hassle free printing to any device.