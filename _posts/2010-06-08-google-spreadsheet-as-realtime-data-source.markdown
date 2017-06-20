---
layout: post
title: 'Google Spreadsheet as Real-Time Data Source'
---
I was just talking with<a href="http://code.google.com/events/io/2010/"> Google I/O</a> events team about keeping events sessions up to date on the conference and event sessions page. Sessions change rapidly and updates are needed by multiple teams in real-time.<p></p>
Web-site(s), support personnel, marketing, etc all need updated information. There are multiple digital and human sources that need the updates.<img style="padding: 15px;" title="Google Data" src="http://d35fa85q7j6dnm.cloudfront.net/google-fusion-tables.PNG" alt="" width="344" height="277" align="right" /><p></p>
There are also multiple people potentially making updates to the data. In the business world people default to using a spreadsheet to store information, with the introduction of <a href="http://docs.google.com">Google Docs</a> you can easily share this information from a central location.<p></p>
It is easy to turn on Notification Rules that send email alerts to users when updates are made. Once you follow the link, you can easily see which cell(s) were updated.<p></p>
This can also be an easy way to update other web sites or other non-human sources. You can send email updates to a system email account, when received it can then pull the spreadsheet through the Google Docs API.<p></p>
Thus creating a real-time update system.
<ol class="mainlist">
	<li>The spreadsheet is updated</li>
	<li>Notification is sent to system email address.</li>
	<li>System responds to email notification</li>
	<li>Pull spreadsheets</li>
	<li>Updates local data source from spreadsheet content.</li>
</ol>
Now this is pretty complex, it would be easier to make these sites use the spreadsheet as a direct data source. If your in the business you know this isn't always possible. People use their own data sources and protocols, they just need an update from time to time.<p></p>
This process uses an existing set of tools (Google Docs), speaking in an existing language people are used to (spreadsheets) to quickly create a central data source that can updated and notify all human and system users in real-time when updates occur.<p></p>
As Google continues their move in the Cloud Storage market with <a href="http://docs.google.com">Google Docs</a>, <a href="http://tables.googlelabs.com">Fusion Tables</a>, <a href="http://code.google.com/securedataconnector/">Google Secure Data Connector</a> and <a href="http://code.google.com/apis/storage/">Google Storage for Developers</a> there are an amazing number of ways to use them as a collaborated, centralized data store.