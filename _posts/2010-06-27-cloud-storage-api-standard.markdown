---
layout: post
title: 'Cloud Storage API Standard'
---
<img class="alignnone" style="padding: 15px; border-color: #000000;" title="Cloud Storage" src="http://kinlane-productions.s3.amazonaws.com/cloud.jpeg" border="1" alt="" width="250" align="right" />I was reviewing a <a href="http://www.kinlane.com/2010/06/cloud-storage-with-cloudberry-backup/">cloud backup product</a>, <a href="http://cloudberrylab.com/default.aspx?page=cloudberry-backup" target="_blank">CloudBerry Backup</a> yesterday. Each time I try a new cloud storage product I can't help think how we need interroperability between all the cloud storage providers.<p></p>
I would like to see a single client that could work with different cloud storage providers. Andy from Cloudberry points out this is difficult because of different approaches to cloud storage and the way their APIs work.<p></p>
A standard for cloud storage is needed. <em><strong>Is Amazon S3 already the standard for cloud storage?</strong></em> Many of the well known elements of the <a href="http://developer.amazonwebservices.com/connect/entry.jspa?externalID=123" target="_blank">Amazon S3 API </a>are:
<ul class="mainlist">
	<li>RESTful Interface</li>
	<li>Buckets</li>
	<li>Objects</li>
	<li>ACL</li>
</ul>
Several other providers have already given Amazon's API the nod as the standard, even <a href="http://code.google.com/apis/storage/docs/developer-guide.html" target="_blank">Google cites this under cloud storage interoperability</a>. <a href="http://www.dunkel.de/s3/" target="_blank">Dunkel cloud storage in Germany</a> even claims that they are Amazon S3 storage compliant.<p></p>
With a common standard it would be easy for cloud storage clients to offer a diverse amount of storage providers, all you would have to do is change the request endpoint (URI) and your data would route to your preferred provider.