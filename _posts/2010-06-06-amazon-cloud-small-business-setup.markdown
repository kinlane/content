---
layout: post
title: 'Amazon Cloud Small Business Setup'
---
<img style="padding: 10px;" title="Amazon Web  Services" src="http://awsmedia.s3.amazonaws.com/logo_aws.gif" alt="" width="164" height="60" align="right" />I have been in the <a href="http://aws.amazon.com/console/">Amazon Console</a> all night scaling down infrastructure after 3 months of events and conferences.  This year our Amazon spend was double during the event season.  Last year I pushed what my budget would allow to achieve better performance, it paid off.  This year I got the thumbs up to push even further (even though I think I may have pushed a little further than I should have), with the amount to spend on processor power.<p></p>
Anyways, while data was moving around and <a href="http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=171">Amazon  Machine Images (AMI)</a> were being created last night I was playing in the <a href="http://aws.amazon.com/console/">Amazon Console</a>.   I really think the Amazon platform is really ready for mainstream small business cloud deployments.<p></p>
Most small business I have worked with have minimal needs regarding Internet technologies that fall under these areas:
<ul class="mainlist">
	<li>Server / Processing Power</li>
	<li>File Storage and Access</li>
	<li>Email</li>
	<li>Load Balancing for scaling but mostly for maintenance and redundancy.</li>
	<li>Backup</li>
	<li>Database</li>
</ul>
That would cover most of the needs for 75% of the small businesses I've worked with.  Now these are usually business with 5-200 employees and less than 25 Million in revenue.  Amazon has really brought together a set of tools that can deliver a complete package for small business:
<ul class="mainlist">
	<li>Serve / Processing Power with <a href="http://aws.amazon.com/ec2/">Amazon EC2</a></li>
	<li>File Storage and Access with <a href="http://aws.amazon.com/s3/">Amazon S3</a></li>
	<li>Email with<a href="http://aws.amazon.com/ec2/"> Amazon EC2</a> and <a href="http://aws.amazon.com/s3/">Simple Notification (SNS)</a></li>
	<li>Load Balancing with <a href="http://aws.amazon.com/autoscaling/">Amazon Auto Scaling</a> and <a href="http://aws.amazon.com/elasticloadbalancing/">Elastic Load Balancing</a></li>
	<li>Backups with <a href="http://developer.amazonwebservices.com/connect/kbcategory.jspa?categoryID=171">Amazon Machine Images (AMI)</a> and backup storage at <a href="http://aws.amazon.com/s3/">Amazon  S3</a></li>
	<li>Database with <a href="http://aws.amazon.com/ec2/">Amazon EC2</a>, <a href="http://aws.amazon.com/simpledb/">Amazon Simple Database</a> or <a href="http://aws.amazon.com/rds/">Amazon Relational Database (RDS)</a></li>
</ul>
Most of these tools are available within the <a href="http://aws.amazon.com/console/">Amazon Console</a>, and everything is available programatically through the Amazon Web Services API. I run our entire business in the cloud. My company WebEvents Global has some unique needs around scaling our infrastructure for events, but beyond that it is a pretty standard business operation.<p></p>
I see a clear vision of how a company can completely operate in the clouds and really define their IT operations, establish benchmarks for what things costs, and take control over their IT infrastructure and make it scalable and resilient in many ways through deploying to the Amazon cloud.<p></p>
I'm going to keep writing on this subject as more and more small to medium business are looking to move on to the cloud.