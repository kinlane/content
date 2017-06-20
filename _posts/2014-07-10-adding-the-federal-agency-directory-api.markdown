---
layout: post
title: 'Adding The Federal Agency Directory API'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-hiearchy.png" alt="" width="200" align="right" /></p>
<p>I wanted to create an APIs.json containing all three of the APis available at www.usa.gov. Before I could create the APIs.json, I needed a Swagger API definition for each of the APIs--first up is the <a href="http://www.usa.gov/About/developer-resources/federal-agency-directory/index.shtml">Federal Agency Directory API</a>.</p>
<p>I went to the home page for the&nbsp;Federal Agency Directory API, and was happy to see they had <a href="http://www.usa.gov/About/developer-resources/federal-agency-directory/interactivedoc.shtml#!/contacts">interactive documentation</a> already for the API, and even better it was Swagger. The machine readable API definition was one version older than what I'm using, but hey, let's go with it.&nbsp;</p>
<p>I <a href="http://www.usa.gov.apievangelist.com/federal-agency-directory-api.html">added a page for the&nbsp;Federal Agency Directory API</a>, in the Github repository, and pointed the interactive API documentation to the existing Swagger API definition, and voila, we have documentation.</p>
<p>My life was made easier, because there was already a Swagger API definition, but also the API has CORS enabled, which allows me to pull the JSON, across domain, and generate interactive documentation.&nbsp;</p>
<p>Alright, one API down, two to go.</p>