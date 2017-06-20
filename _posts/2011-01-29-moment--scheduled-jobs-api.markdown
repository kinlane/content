---
layout: post
title: 'Moment - Scheduled Jobs API'
---
A big part of the web applications I build, is usually some sort of jobs management. Most functionality is triggered based upon user generated events. However there are many times where I need to schedule something as a job.<p></p>
I run most of my web applications on a Windows 2008 server, this is the platform I'm most familiar with.  So I use the task scheduler built into the platform.
<a href="http://momentapp.com/" target="_blank"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/moment-jobs-api.png" alt="" align="right" /></a>
When I migrate applications off my native development environment I need a better way to trigger scheduled jobs.<p></p>
I found <a href="http://momentapp.com/" target="_blank">Moment</a>, a Software as a Service (SaaS) for scheduling jobs.  They provide a simple <a href="http://momentapp.com/" target="_blank">RESTful API for scheduling HTTP based jobs</a> you need to run.<p></p>
I tend to just create my jobs as simple <a href="http://www.kinlane.com/category/php/">PHP</a> scripts and expose them at a non-indexed public URL. So Moment is a great solution.<p></p>
Its good to see useful utility APIs that everyone can use, doing one thing, and doing it well!