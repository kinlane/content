---
layout: post
title: 'Amazon Security Groups for EC2'
---
<img class="alignnone" style="padding: 20px;" title="Three-Tier Architecture with Amazon" src="http://aws.typepad.com/.a/6a00d8341c534853ef0133f0fc1980970b-500wi" alt="" width="300" align="right" />I was working on the <a href="http://www.kinlane.com/2010/06/small-business-it-review/">review of my small business IT infrastructure</a> today, which includes our servers at Amazon EC2. As I was looking at my "server role" definitions and the corresponding Amazon EC2 Security Groups I saw a new blog post come in from Amazon Web Services.<p></p>
They put together an overview of <a href="http://aws.typepad.com/aws/2010/06/building-three-tier-architectures-with-security-groups.html">building three-tier architectures with security groups</a>. I learned a few things while reading which will hopefully help be better setup my infrastructure:
<ul class="mainlist">
	<li>You can reference other security groups instead of IP addresses when adding entries</li>
	<li>Creating security for external users such as vendors or development groups</li>
	<li>Security groups filters traffic internally and externally.</li>
</ul>
So this was an eye opener about truly securing your three-tier architecture. I have the web and database server roles, but the application role is a new layer I hadn't considered.<p></p>
I also have other role based layers for development (subversion), and content (FTP). Also have mail specific SMTP and POP security layers.<p></p>
I will be upgrading my <a href="http://www.kinlane.com/category/amazon/amazon-ec2/">Amazon EC2</a> security structures based upon what I've learned today, and include in my <a href="http://www.kinlane.com/2010/06/small-business-it-review/">cloud IT infrastructure</a> review strategy.