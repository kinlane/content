---
layout: post
title: 'Improved Google Chrome Plug-In Security'
---
<img class="alignnone" style="padding: 20px;" title="Google Chrome" src="http://kinlane-productions.s3.amazonaws.com/google-chrome-logo.jpg" alt="" width="282" height="180" align="right" />The Chromium team talked about <a href="http://blog.chromium.org/2010/06/improving-plug-in-security.html">improved Google Chrome plug-in security</a> today. Apparently we are seeing more and more security exploits targeting browser plug-ins. Since many plug-ins are ubiquitous, they pose the most significant risk to users. To better protect Google Chrome users from the threat of plug-in exploits, Google announced a couple of initiatives:
<ul class="mainlist">
	<li>More powerful plug-in controls: Google Chrome now has the ability to disable individual plug-ins or to operate in a domain whitelist mode whereby only trusted domains are permitted to load plug-ins.</li>
	<li>Autoupdate for Adobe Flash Player: By including Adobe Flash Player -- the most popular plug-in -- with Google Chrome, browsers can re-use Google Chrome's powerful autoupdate strategy and minimize the window of risk for patched vulnerabilities.</li>
</ul>
Other ways Google is attacking the problem:
<ul class="mainlist">
	<li>Integrated PDF viewing: We have announced an integrated PDF viewer plug-in running inside Google Chrome's sandbox. This will make it harder for PDF-based vulnerabilities to result in the persistent installation of malware.</li>
	<li>Protection from out-of-date plug-ins: Medium-term, Google Chrome will start refusing to run certain out-of-date plug-ins (and help the user update).</li>
	<li> Warning before running infrequently used plug-ins: Some plug-ins are widely installed but typically not required for today's Internet experience. For most users, any attempt to instantiate such a plug-in is suspicious and Google Chrome will warn on this condition.</li>
	<li> A next generation plug-in API: Pepper makes it easier to sandbox plug-ins.</li>
</ul>
I'm building my first Google Chrome Plug-In right now to manage a keyword network, and managing linking within blogs. It is good to learn more about the security behind the scenes.