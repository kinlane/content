---
layout: post
title: 'Adding The Social Media Registry API'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-twitter-icon.png" alt="" width="200" align="right" /></p>
<p>I wanted to create an APIs.json containing all three of the APis available at www.usa.gov. Before I could create the APIs.json, I needed a Swagger API definition for each of the APIs--next up is the <a href="http://www.usa.gov/About/developer-resources/social-media-registry.shtml">Social Media Registry API</a>.</p>
<p>I went to the home page for the&nbsp;Social Media Registry API, and unlike the Federal Agency Directory&nbsp;API, there was not already a Swagger API definition. I got to work handcrafting my own--the interface is pretty simple, it didn't take much work.</p>
<p><a href="http://www.usa.gov.apievangelist.com/social-media-registry-api.html">I added a page for the&nbsp;Social Media Registry API</a>, in the Github repository, and pointed the interactive API documentation to the new Swagger API definition, and fired up the interactive documentation.</p>
<p>Just like with the Federal Agency Directory&nbsp;API,&nbsp;CORS was enabled, which allows me to pull the JSON, across domain, and generate interactive documentation.&nbsp;</p>
<p>Alright, two API down, one more to go.</p>