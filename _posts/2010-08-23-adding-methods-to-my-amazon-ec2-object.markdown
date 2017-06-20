---
layout: post
title: 'Adding Methods to my Amazon EC2 Object'
---
<img class="alignnone" style="padding: 15px;" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />I am needing more programmatic control over my <a href="http://www.kinlane.com/category/amazon/amazon-ec2/">Amazon EC2</a> environment. I am rebuilding all server instances on my Amazon Web Services network.<p></p>
I needed to reconfigure using EBS Volumes for file and data storage, and upgrade the operating systems and some applications while I'm at it.<p></p>
So I'm creating all new AMI as well as reconfiguring my snapshot strategy. The central object I use for programmatic manipulation of Amazon was limited.<p></p>
I need to add some methods for managing the Amazon EC2 Volumes:
<ul class="mainlist">
	<li>CreateVolume</li>
	<li>DescribeVolumes</li>
	<li>AttachVolume</li>
	<li>DetachVolume</li>
	<li>DeleteVolume</li>
</ul>
I'm going to need to automate the create of snapshots as well, so I added the following methods:
<ul class="mainlist">
	<li>CreateSnapshot</li>
	<li>DescribeSnapshots</li>
	<li>DescribeSnapshotAttribute</li>
	<li>DeleteSnapshot</li>
</ul>
This will give me additional control beyond just creating and managing instances. With my new EBS framework I have more granular control over different file and data stores for taking snapshots, etc.<p></p>
With this more granular control over drives and their files and data, plus I was just able to offload a lot of "heavy files" like audio, flash, pdf, images, etc. <a href="http://www.kinlane.com/2010/06/store-all-files-at-amazon-s3/">storing all the files at Amazon S3</a>.
