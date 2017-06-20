---
layout: post
title: 'New Access Policies for Amazon S3 Buckets'
---
<a href="http://aws.amazon.com/" target="_blank"><img class="alignnone" style="padding: 15p;" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="282" height="187" align="right" /></a><a href="http://aws.typepad.com/aws/2010/07/amazon-s3-bucket-policies-another-way-to-protect-your-content.html" target="_blank">Amazon Web Services released support for Bucket Policies within Amazon S3 Cloud Storage today</a>. <a href="http://docs.amazonwebservices.com/AmazonS3/latest/dev/index.html?UsingBucketPolicies.html" target="_blank">Bucket policies</a> provide access control management for Amazon S3 buckets and for the objects in them using a single unified mechanism. The policies are expressed using whats called Access Policy Language, that enables centralized management of permissions.<p></p>
Access Control Lists (ACLs) can only be used to grant permissions on individual objects, policies can either add or deny permissions across all of the objects within a single bucket. You can use regular expression operators, so that you can control access to groups that begin with a common prefix or end with a specific file extension such as ".pdf, word, or .html documents<p></p>
Policies can include references to:
<ul class="mainlist">
	<li> IP addresses</li>
	<li>IP address ranges in CIDR notation</li>
	<li>Dates</li>
	<li>User Agents</li>
	<li> HTTP referrer</li>
	<li>http and https</li>
</ul>
<img class="alignnone" style="padding: 15px;" title="Amazon S3 Bucket" src="http://kinlane-productions.s3.amazonaws.com/bucket.jpg" alt="" width="250" align="right" />This really gives me much more granular level control over Amazon S3 buckets. I was just having problems with <a href="http://www.kinlane.com/2010/06/store-all-files-at-amazon-s3/" target="_blank">storing all my server files centrally at Amazon S3</a> because I couldn't establish settings for entire buckets. I have been distracted by other work lately and with the Fourth of July holiday. Now I can set up a bucket policy to:
<ul class="mainlist">
	<li>Allow Comprehensive Write Access</li>
	<li>Access from Specific Networks</li>
	<li> Allow Access from Specific Application using User Agent</li>
</ul>
I am reviewing my file management policies for <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a> right now to see how I can create different levels of access. This will definitely make it easier for me to require all workstations, servers and web applications to store ALL files in <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a> Buckets.