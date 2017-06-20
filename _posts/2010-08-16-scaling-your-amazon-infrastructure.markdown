---
layout: post
title: 'Scaling Your Amazon Infrastructure'
---
<img style="padding: 15px;" title="Amazon Web Services" src="http://kinlane-productions.s3.amazonaws.com/AWS_LOGO_CMYK.jpg" alt="" width="250" align="right" />I am still processing a great post at <a href="http://highscalability.com/">High Scalability</a> called, <a href="http://highscalability.com/blog/2010/8/16/scaling-an-aws-infrastructure-tools-and-patterns.html" target="_blank">Scaling an AWS infrastructure - Tools and Patterns</a>. They cover several tools you can use to take advantage of Amazon's Web Service and suggest an architectural model you should adopt for a scalable infrastructure in the cloud.<p></p>
They suggest the following tools for managing your amazon scaling:
<ul class="mainlist">
	<li><a href="http://www.puppetlabs.com/" target="_blank">Puppet</a> for managing your Amazon EC2 instances</li>
	<li><a href="http://www.capify.org/index.php/Capistrano" target="_blank">Capistrano</a> for cloud task automation</li>
	<li><a title="Site de Centreon" href="http://www.centreon.com/">Centreon</a>/<a title="Site de Nagios" href="http://www.nagios.org/">Nagios</a>, <a title="Site de Zabbix" href="http://www.zabbix.com/">Zabbix</a>, <a title="Site de Cacti" href="http://www.cacti.net/">Cacti </a>and <a title="Site de  Munin" href="http://munin.projects.linpro.no/">Munin</a> for cloud monitoring</li>
	<li><a title="Site de Syslog-NG" href="http://www.balabit.com/network-security/syslog-ng/">Syslog-NG</a> for centralized log file management</li>
</ul>
They even cover several tools for optimized data access:
<ul class="mainlist">
	<li>Structured relational data with MySQL or a PgSQL on Amazon EC2</li>
	<li>Storage for more volatile data with tools like <a title="Site de Redis" href="http://code.google.com/p/redis/">Redis</a>, <a title="Site de  Tokyo Tyrant" href="http://1978th.net/tokyotyrant/">Tokyo Tyrant</a>/<a title="Site de Tokyo Cabinet" href="http://1978th.net/tokyocabinet/">Tokyo Cabinet</a>, <a title="Site de MemcacheDB" href="http://memcachedb.org/">MemcacheDB</a>.</li>
</ul>
There are a lot of great points on how to scale your Amazon Cloud infrastructure. Exciting to see different approaches to scaling with Amazon Ec2 and S3 and throwing in some innovative open source tools that make the process much easier and powerful.