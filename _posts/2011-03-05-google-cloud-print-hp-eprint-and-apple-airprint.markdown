---
layout: post
title: 'Google Cloud Print, HP ePrint, and Apple Airprint'
---
I've been spending time learning about the three major platform we think about when we hear the term <strong><em>cloud printing</em></strong>.
<ul class="mainlist">
	<li><a title="Apple Airprint" href="http://www.kinlane.com/2011/03/apple-airprint/">Apple Airprint</a></li>
	<li><a title="HP ePrint" href="http://www.kinlane.com/2011/03/hp-eprint-web-connected-printers/">HP ePrint</a></li>
	<li><a title="Google Cloud Print" href="http://www.kinlane.com/2011/03/google-cloud-print/">Google Cloud Print</a></li>
</ul>
As I'm learning about the details of each printing platform, I can't help but compare them against each other. Here are some things I'm tracking on:
<p style="padding-left: 30px;"><em><a title="Apple Airprint" href="http://support.apple.com/kb/ht4356">Apple Airprint</a> provides printing on IOS and Mac platforms over a local network to HP web connected printers.</em>
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/apple-airprint/ipad-and-airprint.jpg" alt="" width="300" align="right" />
<p style="padding-left: 30px;"><em><a title="HP ePrint" href="http://h30495.www3.hp.com/about/eprint">HP ePrint</a> provides printing over the Internet to any HP web connected printer.  Each printer registers itself with the HP ePrint Center and gets assigned an email address.    Print jobs are delivered via email to each printer.</em>
<p style="padding-left: 30px;"><em><a title="Google Cloud Print" href="http://code.google.com/apis/cloudprint/docs/overview.html">Google Cloud Print</a> provides printing over the Internet to any local, office or commercial printer.</em>
<p style="padding-left: 30px;"><em>Apple isn't quite in the same league as HP and Google Cloud Print.   Airprint only provides local network printing.  HP provides a cloud system dedicated to their HP web connected printers, while Google is building a cloud system that is accessible by any printer.</em>
<p style="padding-left: 30px;"><em>Airprint is integrated into the IOS and Mac OS, and Google Cloud Print is integrated into Google Apps and the Google Chrome OS.    HP doesn't have this type of integration exposure.</em>
<p style="padding-left: 30px;"><em>Google Cloud Print provides custom application development using Google Apps and provides document resources through Google Docs Template Gallery.</em>
<p style="padding-left: 30px;"><em>HP ePrint provides a custom application platform for their printers, and home and business document resources through their Marketsplash, and Creative Studio for home and business.</em>
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/HP-ePrint/hp_eprint_center.jpg" alt="" width="200" align="right" />
<p style="padding-left: 30px;"><em>HP uses email to register and route print jobs to printers over the Internet.</em>
<p style="padding-left: 30px;"><em>Google uses an API to register printers and fetch print jobs, then uses <a class="zem_slink" title="Google Talk" rel="homepage" href="http://www.google.com/talk/">GTalk</a>, which employs XMPP, a messaging and presence protocol used to route print job notifications.</em>
<p style="padding-left: 30px;"><em>I'm not sure what Apple uses to route register printers and route print jobs yet.</em>
Its an interesting mix of cloud printing technology, and perspectives on what cloud printing is:
<p style="padding-left: 30px;"><em>Apple has IPhone, IPad, but Airprint can only print locally at the current time.</em>
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/google-cloud-print/google-cloud-print.png" alt="" width="250" align="right" />
<p style="padding-left: 30px;"><em>HP ePrint can only print to HP printers, but is available anywhere over the Internet.  HP is also developing integration with Google Cloud Print, and also Apple Airprint can only print to HP web connected printers.</em>
<p style="padding-left: 30px;"><em>Google has the Android platform, Google Apps and Google Chrome OS.  Google also is accessible on the IPhone and IPad as well as having an application on the HP ePrint platform. Google provides support for any printer, new or old as well provides access to commercial printers.</em>
Currently Google seems to have the lead with a much wider platform and accessibility.  Although there is no questioning Apples dominance in the mobile market, and HP in the printer market.<p></p>
It will be an interesting year to see where these cloud print players go with their platforms.
