---
layout: post
title: 'New Twitter Consumes Their Own API'
---
<a href="http://blog.twitter.com/2010/09/better-twitter.html" target="_blank">Twitter released a brand new twitter.com today</a> with all kinds of <a href="http://twitter.com/newtwitter" target="_blank">new features</a>. The feature that really stands out for me is now the main twitter.com web site runs off the <a href="http://dev.twitter.com/" target="_blank">Twitter API</a>.<p></p>
The Twitter mobile site and Twitter Iphone and IPad apps all run using the Twitter API, but now the most popular Twitter client does as well.<p></p>
This is a very important practice for businesses to adopt. It will put you in the shoes of your developers and API consumers....essentially eating your own dog food.<p></p>
In 2000 I started a web development company with my wife. I developed a custom content management platform for delivering web sites and applications for my customers. By 2006 I had reached version 3.0 running on Classic ASP and SQL Server 2000, and faced the challenge of migrating to .NET for my Version 4.0. I made the decision to move away from the Microsoft platform and went with PHP and MySQL for my version 4.0.<p></p>
Over a summer I sat down to develop my Version 4.0. In addition to the language and database change I made another radical decision. I was going to start with the API.<img class="alignnone" style="padding: 15px;" title="Twitter" src="http://kinlane-productions.s3.amazonaws.com/Twitter-Logo.jpg" alt="" width="282" height="180" align="right" /><p></p>
My version 3.0 had 180 separate system I had hand coded, for version 4.0 I chose 75 of the most important and began to develop a set of RESTful web services to drive these systems.<p></p>
Once I had the database and web services developed I began to create essentially a set of PHP SDK libraries and UI elements that consumed these web services. This became the version 4.0 of my content management system.<p></p>
I remember several technical folks with partners I had at the time telling me that was the dumbest thing they've heard. APIs aren't for your primary systems? They are for 3rd party integration. I stood by my decision and developed several successful web applications.<p></p>
Unfortunately I sold my business as part of my divorce with my wife, and when I was packaging up sites to deliver the code to clients I remember several other developers commenting on how strange my decision was. However I did get a couple folks say how interesting it was and were very happy with the architecture I delivered.<p></p>
Very smart move Twitter, I recommend other companies to do the same with their applications.
