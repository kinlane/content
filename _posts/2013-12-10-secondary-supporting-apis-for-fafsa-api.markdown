---
layout: post
title: 'Secondary Supporting APIs For FAFSA API'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-flying-buttress.jpg" alt="" width="150" align="right" /></p>
<p>I made the core read / write endpoints for the FAFSA applications, this week I focused on deploying a series of read only APIs to support developers when building FAFSA driven applications in education.</p>
<p>While I'm still evaluating some potential other datasets here are the ones I've published so far:</p>
<ul class="mainlist">
<li><strong>FAFSA Fields </strong>- An endpoint providing a list of fields on the FAFSA form</li>
<li><strong>States</strong> - An endpoint providing a list of states and provinces in the US and Canada</li>
<li><strong>Rejection Codes</strong> - Potential rejection codes for the FAFSA application</li>
<li><strong>Conditional Procedures</strong> - Conditional procedures to process a FAFSA application</li>
</ul>
<p>I'm currently queueing up another supporting API endpoint of secondary schools in the United States. It is a rather large data set, so it is taking some time to process and turn into a usable API.</p>
<p>If there are other API endpoints you'd like to see, feel free to submit as an issue on the project's Github repository and I'll consider adding into the project roadmap.</p>