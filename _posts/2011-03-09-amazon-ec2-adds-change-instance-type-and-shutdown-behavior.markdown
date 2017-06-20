---
layout: post
title: 'Amazon EC2 Adds Change Instance Type and Shutdown Behavior'
---
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" /><strong>Amazon Web Services</strong> just released two pretty <a title="Amazon EC2 Enhancements" href="http://aws.typepad.com/aws/2011/03/even-more-ec2-goodies-in-the-aws-management-console.html">significationenhancementsto the Amazon EC2 infrastructure</a>.<p></p>
You can now:
<ul class="mainlist">
	<li><strong>Change Instance Type</strong> -This means that you can scale up or scale down as your needs change. The new instance type must be compatible with the AMI that you used to boot the instance, so you can't change from 32 bit to 64 bit or vice versa.</li>
	<li><strong>Shutdown Behavior</strong> -You can now control what happens when an EBS-backed instance shuts itself down. You can choose to stop the instance (so that it can be started again later) or to terminate the instance.</li>
</ul>
These are two pretty significant features when your working with 24/7, mission critical applications and database that run on EC2.<p></p>
Gone are the days when you shut down an instance and its gone forever, thanks to EBS and the new and Amazon EC2.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://aws.typepad.com/aws/2011/03/even-more-ec2-goodies-in-the-aws-management-console.html">Even More EC2 Goodies in the AWS Management Console</a> (aws.typepad.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://web2.sys-con.com/node/1687874">Amazon Going PaaS? Introducing Elastic Beanstalk</a> (web2.sys-con.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.cloudave.com/10183/aws-cloudformation-poaching-the-ecosystem/">AWS CloudFormation: Poaching The Ecosystem?</a> (cloudave.com)</li>
</ul>
