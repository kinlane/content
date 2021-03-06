---
layout: post
title: 'FAFSA API - PHP Server'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/php-logo-300.png" alt="" width="200" align="right" /></p>
<p>Now that I have the <a href="http://ed-data.github.io/fafsa-api/2013/11/25/fafsa-api-definition/">FAFSA API definition</a> and the <a href="http://ed-data.github.io/fafsa-api/2013/11/26/setting-up-my-database-for-fafsa-api/">database setup</a>, I now need an actual API. I'm going to build my initial API in PHP, using the <a href="http://www.slimframework.com/">Slim REST Framework</a>, hosted on an Amazon EC2 instance. In the future I will build a Python, Ruby and Node.js version as well, but for now its PHP.</p>
<p>I setup an API endpoint at fafsa.api.publicprivatesector.org, then published the Slim framework. I like using Slim because I all really have to do is create single include files for each API resource, add an include to the index file and boom, I have an API.</p>
<p>I have the following code for the first draft of my applications/ endpoint:</p>
<script src="https://gist.github.com/kinlane/7715523.js"></script>
<p>Since this API is read and write I need to next secure the API somehow, forcing developers to register for app keys before they can make calls against the API. I'm going to use <a href="http://bit.ly/13esk6Q">3Scale</a> to do this, because the platform allows me to do it without incurring any setup charges. I will only have to pay if I generate a significant amount of traffic.</p>
<p>This is the just the first basic version of the FAFSA API, providing me with the CRUD operations I will need. Once I get it secured and interactive documentation setup I can play with more and add more features, polishing the interface further.</p>