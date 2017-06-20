---
layout: post
title: 'Store All Files at Amazon S3'
---
<a href="../category/amazon/amazon-s3/">Amazon S3</a> <a href="http://www.kinlane.com/2010/06/cloud-storage-api-standard/">cloud storage</a> has changed the way I manage files on my networks. I am centralizing all file storage across my web site and applications to Amazon S3. All heavy file types:
<img style="padding: 15px;" title="Amazon S3 File Storage" src="http://kinlane-productions.s3.amazonaws.com/filetypes-2.png" alt="" width="282" height="187" align="right" />
<ul class="mainlist">
	<li>.jpg</li>
	<li>.gif</li>
	<li>.png</li>
	<li>.tif</li>
	<li>.doc / .docx</li>
	<li>.xls / .xlsx</li>
	<li>.fla</li>
	<li>.pdf</li>
	<li>.vcs</li>
	<li>.zip</li>
</ul>
Should all be stored in central buckets that reflect a project client tenancy structure. Each server has a mapped network drive of <strong>F:</strong> to proper file bucket.<p></p>
All images will be referred to using <span style="text-decoration: underline;">http://file.clientdomain.com.</span><p></p>
<img style="padding: 15px;" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="282" height="187" align="right" />All developers, project managers and clients can connect to each file store using:
<ul class="mainlist">
	<li>FTP</li>
	<li>Firefox <a href="https://addons.mozilla.org/en-US/firefox/addon/3247/" target="_blank">S3Fox</a></li>
	<li>Mapped network drive using <a href="https://www.jungledisk.com/" target="_blank">Jungle Disk</a></li>
</ul>
This will take all files out of the general population on servers. Web file version control will run faster and we can access files centrally across all servers. Then files will :
<ul class="mainlist">
	<li>Exist centrally, independent of any permanent or temporary <a href="http://www.kinlane.com/category/amazon/amazon-ec2/">Amazon EC2</a> instance</li>
	<li>Take advantage of <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a> versioning</li>
	<li>Take advantage of <a href="../category/amazon/amazon-s3/">Amazon S3</a> Cloudfront regional distribution</li>
</ul>
Managing files across hundreds of projects, clients, developers, and users isn't easy. Centralizing them at Amazon S3 and backing up to another cloud provider for backups makes things more manageable.