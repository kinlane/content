---
layout: post
title: 'Adding Data Page For FAFSA'
---
<p><a href="http://ed-data.github.io/fafsa-api/data.html"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-json-data-store.png" alt="" width="150" align="right" /></a></p>
<p>Since this is primarily a prototype API, and not meant for production integration, I wanted to make sure that all the data behind this project is available for download.</p>
<p>I added all JSON files to the master repository, and added a <a href="https://raw.github.com/ed-data/fafsa-api/master/data.json">data.json index</a>, with a page to <a href="http://ed-data.github.io/fafsa-api/data.html">view all the data files</a>. Currently I have 5 data files:</p>
<ul class="mainlist">
<li>FAFSA Form Fields</li>
<li>FAFSA Form Conditional Procedures</li>
<li>FAFSA Form Rejection Codes</li>
<li>States</li>
<li>Schools</li>
</ul>
<p>These are the JSON exports of the MySQL database I'm using to drive the API. It should be pretty easy for you to download and generate your own API, or use however you want in your application.</p>
<p>The goal is make the API, data behind, and all the supporting resources open and accessible.</p>