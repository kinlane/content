---
layout: post
title: 'My Only 2 Complaints About Amazon EC2'
---
Don't get me wrong...I love Amazon Web Services and EC2, it has changed the way I do business. I rocks.<p></p>
So tonight I was doing some server maintenance and backing up many server instances as AMI. This gives me a image snapshot of that production server to use while scaling and / or restoring in the event of failure.<p></p>
Any other time the EC2 services are awesome but tonight my 2 complaints are evident:<p></p>
1) Only 1 IP Address per instance. PLease give me multiple IP Addresses per instance.<p></p>
2) When I bundle a Windows 2003 Web Server Instance it KILLS ANY SSL CERTIFICATES! It does something to the permissions of the certs in store. I blogged about this before. I have .pfk backup files and I just delete and import. Still it is a pain to do across MANY web server instances.<p></p>
So I only backup machine instances using AMI once a month.