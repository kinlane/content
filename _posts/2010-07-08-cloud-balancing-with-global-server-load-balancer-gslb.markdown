---
layout: post
title: 'Cloud Balancing with Global Server Load Balancer (GSLB)'
---
Last year I moved web site, database and email services for the <a href="https://www.sapandasug.com/">SAP SAPPHIRE</a> event to the Amazon Cloud. We needed to scale our infrastructure dramatically to support the event for about 4 months out of the year. This was our second year running the conference in the Amazon Cloud and we were able to scale up nicely to handle the traffic. There were still issues. <a href="http://www.zeus.com/" target="_blank"><img class="alignnone" style="padding: 15px;" title="Global Server Load Balancing" src="http://kinlane-productions.s3.amazonaws.com/cloud-computing/Global-Load-Balancing.PNG" alt="" width="286" height="192" align="right" /></a><p></p>
<strong>Global Traffic and Latency</strong><p></p>
We ran systems to support SAPPHIRE Frankfurt as well as the <a href="http://www.sapphirenow.com/">Virtual SAPPHIRE</a>. So our traffic was from all over the world, and specifically in Europe for a large portion. Availability and latency with various web applications become critical. I am research different methods for addressing not only for SAPPHIRE next year but a year round calendar of events for SAP, Google and other clients.<p></p>
I'm researching DNS-based Global Server Load Balancing or GSLB solutions such as <a href="http://dyn.com/dynect" target="_blank">Dynect</a>. GSLB allows you to distribute application load between data centers or cloud providers in any zone or global region you choose. Traffic can be routed based upon:
<ul class="mainlist">
	<li>User Geography</li>
	<li>Server Capacity / Availability</li>
	<li>Geographic Based Laws and Regulation</li>
</ul>
Based upon a users location when they load my application at <em><strong>registration.eventdomain.com</strong></em> and they are located in Europe, using <a href="http://www.kinlane.com/category/dns/">DNS</a> I can route them to registration-eu.domain.com which is routed to server instances I have deployed in Europe using Amazon EC2. Using Global Server Load Balancing I can:
<ul class="mainlist">
	<li>Balance server traffic more evenly across my cloud infrastructure</li>
	<li>Create a better user experience by routing them to servers closest to them.</li>
	<li>Avoid Internet outages and bottle necks</li>
</ul>
Overall this will increase application performance and better meet business objectives around delivery web applications to users. As I"m supporting events and conferences in more locations around the world, this type of web application delivery using <a href="http://www.kinlane.com/category/infrastructure-as-a-service-iaas/">Infrastructure as a Services</a> (IaaS) and Global Server Load Balancing (GLSB) is becoming critical.<p></p>
<strong>Update: </strong> I am also researching <a href="http://www.zeus.com/" target="_blank">Zeus</a> as part of our <a href="http://www.zeus.com/" target="_blank">Global Server Load Balancer strategy</a>, and they were so kind to let us use their image.