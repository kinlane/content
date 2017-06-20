---
layout: post
title: 'Adding A New Alpha Endpoint To Tell Me How Big My API Endpoints Are'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-scope.png" alt="" width="250" align="right" /></p>
<p>I've spent a lot of time this year, breaking up earlier versions of my APIs, into smaller, more "micro" services. As I evolve these APIs, I'm wanting to better understand how they grow, and increase in size. To help me understand how my stack of APIs are growing, <a href="https://kin-lane.github.io/api/">I added a new alpha endpoint to my API API</a>, that allows me to quantify the size of an collections of APIs I want.</p>
<p>To use the new API endpoint, I pass in the URL of an APIs.json file, and the API will iterate through all APIs present, and indexed OADF files. It returns counts for the following areas:</p>
<ul>
<li>paths</li>
<li>verbs</li>
<li>parameters</li>
<li>responses</li>
<li>definitions</li>
</ul>
<p>It is a pretty basic concept, and I'm not entirely sure what the counts ultimately mean, but it is a starting point for me to begin thinking about the scope of my API surface area, and eventually visualizing. At first glance, I can imagine too many paths acting as a warning for overall size for some APIs, while the lack of responses, could mean I should spending more time defining what the API returns.</p>
<p>The how big is my API endpoint is just one of many utility APIs I am crafting that use <a href="http://apisjson.org">APIs.json</a> file to build a better awareness the APIs that exist within its index. My goal is to craft a whole suite of APis that can be used at any stage of the API life-cycle, to streamline operations, and ensure things are running as smooth as possible.</p>