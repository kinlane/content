---
layout: post
title: 'Amazon S3 - Access Logging'
---
I was mapping some subdomains to various <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a> buckets today. I decided to use the new Amazon S3 interface available in the <a href="http://www.kinlane.com/category/amazon/amazon-console/">Amazon Console</a>, instead of S3Fox for a change.<p></p>
I was setting the permissions for a new bucket and I noticed the logging feature for each bucket. For some reason this has escaped me. I see in the <a href="http://developer.amazonwebservices.com/connect/entry.jspa?externalID=422" target="_blank">developers area that S3 Logging has been around for years</a>?<p></p>
<img class="alignnone" title="Amazon S3 Logging" src="http://kinlane-productions.s3.amazonaws.com/amazon/Amazon-S3-Logging.PNG" alt="" width="600" align="center" /><p></p>
Anyways, you can set access logging for each bucket. Seems like a perfect feature to help deal with security concerns about storing data in the clouds. The logging feature is a great tool if you are required keep detailed logs of who accessed your data.