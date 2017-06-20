---
layout: post
title: 'Add An APIs.json For Explore.Data.Gov'
---
<p><a href="http://apisjson.org/"><img src="https://s3.amazonaws.com/kinlane-productions/apis-json/apisdotjson.png" alt="" width="325" align="right" /></a></p>
<p>After <a href="http://explore.data.gov.apievangelist.com/2014/07/10/creating-a-swagger-api-definition-for-federal-executive-agency-domain-api/">creating a machine readable API definition using Swagger for explore.data.gov</a>, I now want to nwo create an <a href="http://apisjson.org/">APIs.json</a>&nbsp;file, which will act as directory of the APIs available at explore.data.gov.&nbsp;</p>
<p>Of course, this isn't the real domain, but if the GSA wants, they can take the APIs.json, and any API definitions, and migrate to their own servers That is one of the goals of this project:</p>
<ol>
<li>Play with the APIs.json format</li>
<li>Make GSA APIs available to APIs.io</li>
<li>Get the attention of GSA so they will a) Copy APIs.json b)Copy the Swagger API definitions, and publish them both at explore.data.gov (then keep up to date)</li>
</ol>
<p>With that in mind, I've now published a machine readable APIs.json file, which provides an index of the APIs I've created definitions for in Swagger.</p>
<script src="https://gist.github.com/kinlane/341b4bba8c19840c6ab0.js"></script>
<p>When APIs.io is updated to support 0.14 of the APIs.json format, I will submit <a href="http://explore.data.gov.apievangelist.com/apis.json">this APIs.json</a> for indexing. My entry won't register as authoratative, because the APIs.json isn't actually within the explore.data.gov domain. However the APIs I have published here will get indexed, and made available in the API search engine.</p>
<p>I only have the&nbsp;<a href="http://explore.data.gov.apievangelist.com/domains-api.html">Federal Executive Agency Internet Domains API</a> published here currently, but maybe I'l find and publish others here in the future. Until then this project will remain as is.&nbsp;</p>