---
layout: post
title: 'Mobile Data Gathering'
---
While playing around with Google Fusion Tables tonight I came across the <a href="http://code.google.com/p/open-data-kit/">Open Data Kit</a> (ODK).<p></p>
Open Data Kit (ODK) is a suite of tools to help organizations collect, aggregate and visualize their data. The project's goals are to make open-source and standards-based tools which are easy to try, easy to use, easy to modify and easy to scale.<p></p>
The project consists of:
<ul class="mainlist">
	<li><a href="http://code.google.com/p/open-data-kit/wiki/ODKCollect">ODK Collect</a> - ODK Collect is powerful phone based replacement for your paper forms. Collect is built on the <a rel="nofollow" href="http://www.android.com/">Android</a></li>
	<li><a href="http://code.google.com/p/open-data-kit/wiki/ODKAggregate">ODK Aggregate</a> - ODK Aggregate provides a ready to deploy online repository to store, view and export collected data. Aggregate is currently implemented on <a rel="nofollow" href="http://code.google.com/appengine/docs/whatisgoogleappengine.html">Google App Engine</a> and enables free hosting of data on Google's reliable infrastructure.</li>
	<li><a href="http://code.google.com/p/open-data-kit/wiki/ODKManage">ODK Manage</a> - ODK Manage maintains a <a class="zem_slink" title="Database" rel="wikipedia" href="http://en.wikipedia.org/wiki/Database">database</a> of all phones in a deployment to enable remote <a class="zem_slink" title="Device Management" rel="wikipedia" href="http://en.wikipedia.org/wiki/Device_Management">device management</a>. By sending an <a class="zem_slink" title="SMS" rel="wikipedia" href="http://en.wikipedia.org/wiki/SMS">SMS</a> to a deployed phone, Manage can trigger the transfers of forms, data, and applications.</li>
	<li><a href="http://code.google.com/p/open-data-kit/wiki/ODKValidate">ODK Validate</a> - ODK Validate ensures that you have a <a rel="nofollow" href="http://code.javarosa.org/">OpenRosa</a> complaint form -- one that will also work with all the ODK tools.</li>
	<li><a href="http://code.google.com/p/open-data-kit/wiki/ODKVoice">ODK Voice</a> - ODK Voice facilities mapping <a class="zem_slink" title="XForms" rel="wikipedia" href="http://en.wikipedia.org/wiki/XForms">XForms</a> to sound snippets that can be played over a "robo" call to any phone. Responses are collected using the phone's keypad (<a class="zem_slink" title="Dual-tone multi-frequency" rel="wikipedia" href="http://en.wikipedia.org/wiki/Dual-tone_multi-frequency">DTMF</a>) and are automatically aggregated.</li>
</ul>
Cool stuff!<p></p>
Great way to build mobile survey and data gathering applications that can be easily downloaded onto mobile phones such as Google Android.
