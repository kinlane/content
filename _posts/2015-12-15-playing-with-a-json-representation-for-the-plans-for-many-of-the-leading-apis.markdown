---
layout: post
title: 'Playing With A JSON Representation For The Plans For Many Of The Leading APIs'
---
<p><img src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-dollar-sign.png" alt="" width="125" align="right" /></p>
<p>I've long wanted a machine readable way to describe, discover, and compare the pricing of the leading APIs that I track on. I've slowly documented some of the <a href="http://monetization.apievangelist.com/building-blocks.html">common building blocks of how APIs are monetizing their APIs</a>, as well as <a href="http://plans.apievangelist.com/building-blocks.html">the details of the plans that go into platform operations</a>.</p>
<p>As with all of my work, I am not looking to pull a machine readable representation out of thin air. I am taking the API definitions, and <a href="http://apievangelist.com/2015/12/12/apis-in-the-most-mature-sectors-have-pricing-apis/">underlying schemas at play with pricing and planning APIs from AWS and Twilio</a>, and identify other common patterns extracted from the approach of other API providers, from a diverse cross-section of the API sector, to bring this into focus.</p>
<p>To help me establish a common JSON schema that could possibly describe pricing and planning behind common API platforms, I took a look at 60+ providers, to capture a v1 schema:</p>
<script src="https://gist.github.com/kinlane/380618d603810e016d7c.js"></script>
<p>I took a quick pass through these API platforms looking for signs of pricing, as well as other motivations behind the operations. I am now taking a second pass, and actually crafting a JSON representation of each platform, to help me push forward the schema, and better understand where it falls short--here are the first five that I have defined so far:</p>
<p><strong>Alchemy API</strong></p>
<script src="https://gist.github.com/kinlane/3f543dbe8d6856919d31.js"></script>
<p><strong>Algolia API</strong></p>
<script src="https://gist.github.com/kinlane/0603b73be4282e2fc087.js"></script>
<p><strong>Amazon EC2 API</strong></p>
<script src="https://gist.github.com/kinlane/3215c0f7afc2e37ae434.js"></script>
<p><strong>Amazon S3 API</strong></p>
<script src="https://gist.github.com/kinlane/23b091e50bdaf8773d3f.js"></script>
<p><strong>AngelList API</strong></p>
<script src="https://gist.github.com/kinlane/4e48cde1ffccac5319ff.js"></script>
<p>I have over 55 more providers to apply this schema to, before I am even willing to consider it an early start. Here is all of them in a single definition. I only have the plans described for the first five, but many of them do not even have plans, and various couplings with the monetization strategy of their core business.&nbsp;</p>
<p>This is another aspect I should probably clarify. There is a value for each provider that rates the coupling of their API monetization strategy to their core business model. I am not sure what this means, and quickly expanded this to be a four level ranking, pushing beyond just three levels. Overall it seems to be helping me understand the motivations behind the API, in relation to the core business mission of the company or companies that make things go round.</p>
<p>You are welcome to look at all 60+ of the companies I'm looking at, I've published as a Github Gist below. I've already added four or five new ones, and will be pushing forward with more, as I have time. There is still much to flush out, and I still can't compare apples to applies like Amazon compute to Azure compute, or Twilio SMS to Tropo SMS, but I am able to discover APIs who don't have detailed plans, and which ones are only about content generation, or possibly selling products and devices.</p>
<p>I suspect, much like my other API definition work, this API planning specification will continue to evolve as I profile more companies. Hopefully eventually the spec, and the patterns I've defined from the approaches of API providers that are working, will become patterns that other providers can emulate, working to standardize what is possible when searching and ranking the pricing across hundreds or even thousands of API providers.</p>
<script src="https://gist.github.com/kinlane/c38a1822a8cd222af891.js"></script>