---
layout: post
title: 'Securing The FAFSA API With 3Scale'
---
<p><a href="http://bit.ly/13esk6Q"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/api-service-providers/3Scale/3scale-logo.png" alt="" width="225" align="right" /></a></p>
<p>The FAFSA API is a full read and write API, allowing developers to add new financial student aid applications, update, delete and pull details on existing applications.  This is just the first draft of the API interface, which now I need to secure before some discovers its publicly available. Tick, Tock.</p>
<p>I'm going to use <a href="http://bit.ly/13esk6Q">3Scale API architecture</a> to secure the API. 3Scale is dead simple to setup. All I do is sign up for an account and add a few lines of PHP code to lock down the API, requiring developers to sign up for an app key before they can use the API.</p>
<p>For my PHP deployment using the Slim Framework, I just add the 3Scale libraries and verification code to my index file. Now every call to the API will have to go through the 3Scale validation to make sure they have proper app keys, otherwise they just get a 403 Forbidden.</p>
<script src="https://gist.github.com/kinlane/7715646.js"></script>
<p>Now that I have the first draft of the API setup on an AWS EC2 instance and secured with 3Scale, I can setup some interactive documentation using Swagger UI and play with the API some more before I decide what changes and additions I want to make next.</p>