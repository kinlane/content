---
layout: post
title: 'The Reverse Hearbleed Switch'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/heartbleed/heartbleed.jpg" alt="" width="250" align="right" /></p>
<p>We needed a way to get everyone to weaken the SSL they were using, and what better target than <a href="http://www.openssl.org/">OpenSSL</a>, which handles SSL for millions of companies worldwide. Until recently we were not able to infiltrate the OpenSSL team, and with the recent Snowden leaks, we needed to increase the vulnerability of systems across the board as quickly as possible.</p>
<p>In the end, all it took was a story about how there was a bug in the current implementation, with a couple of trusted and verified sources, and leak the story to the press&mdash;the rest will be done by system administrators around the globe.  We wouldn't need to penetrate systems, the system administrators would do it for us--if they believed they were compromised.</p>
<p>The real story is that all the updates is where the security hole is, but nobody is looking for it because they are comforted by the fact that they acted so fast with the rest of the sheep in the systems administration field. Heardbleed was a successful test of a new approach to making systems vulnerable by playing on the fears of the masses.</p>
<p>In the future we won&rsquo;t need to infiltrate systems, we&rsquo;ll just people to do it for us.</p>