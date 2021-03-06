---
layout: post
title: 'Updating to Swagger 2.0'
---
<p><a href="http://swagger.io/"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/api-evangelist/swagger/Swagger-Logo.png" alt="" width="250" align="right" /></a></p>
<p>I gave it some time before I pushed my API definitions forward to use <a href="http://swagger.io/">Swagger 2.0</a>, but I had an opportunity this weekend, and I decided to go for it.&nbsp;</p>
<p>I updated all of the Wwagger API definitions to use Swagger 2.0, and updated to the latest <a href="https://github.com/wordnik/swagger-ui">Swagger UI</a> as well. I like some of the features with the new Swagger, but I still have a couple of issues to figure out.</p>
<p>It also gave me an opportunity to clean up some of my CORS stuff, I noticed I had gone different routes for each API, and now I'm standardizing to use .htaccess file instead of at the Apache web server level.&nbsp;</p>
<p>I will be playing around with what else I can do with Swagger 2.0, like generate client SDKs for each of these API projects.</p>