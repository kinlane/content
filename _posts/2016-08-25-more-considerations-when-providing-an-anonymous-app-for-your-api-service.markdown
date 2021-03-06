---
layout: post
title: 'More Considerations When Providing An Anonymous App For Your API Service'
---
<p><a href="http://apievangelist.com/2016/08/19/providing-an-anonymous-layer-to-your-api-provider-service-like-stoplightio/">I wrote a post the other day about Postman.io having a limited, anonymous&nbsp;version of their API modeling tool</a>. I stumbled across it while I was trying to upgrade my Stoplight.io account. Shortly after I tweeted out the blog post, John Sheehan (<a href="https://twitter.com/johnsheehan">@johnsheehan</a>) from <a href="https://www.runscope.com/">Runscope</a> chimed in with some wisdom on the subject.</p>
<blockquote class="twitter-tweet" data-conversation="none">
<p dir="ltr" lang="en"><a href="https://twitter.com/kinlane">@kinlane</a> we had a &lsquo;one-click trial&rsquo; 24-hour account once, no email required. i regret the hours i wasted building it.</p>
&mdash; John Sheehan (@johnsheehan) <a href="https://twitter.com/johnsheehan/status/766730507685990401">August 19, 2016</a></blockquote>
<blockquote class="twitter-tweet" data-conversation="none">
<p dir="ltr" lang="en"><a href="https://twitter.com/kinlane">@kinlane</a> was basically just used for abusive cases. only one ever converted to a real user</p>
&mdash; John Sheehan (@johnsheehan) <a href="https://twitter.com/johnsheehan/status/766730600774447109">August 19, 2016</a></blockquote>
<blockquote class="twitter-tweet" data-conversation="none">
<p dir="ltr" lang="en"><a href="https://twitter.com/kinlane">@kinlane</a> hurl.it and requestb.in have the same problem. have to hamper them (captcha, cloudflare) to keep up</p>
&mdash; John Sheehan (@johnsheehan) <a href="https://twitter.com/johnsheehan/status/766730729241751552">August 19, 2016</a></blockquote>
<blockquote class="twitter-tweet" data-conversation="none">
<p dir="ltr" lang="en"><a href="https://twitter.com/kinlane">@kinlane</a> if it gets any popularity, you&rsquo;re screwed</p>
&mdash; John Sheehan (@johnsheehan) <a href="https://twitter.com/johnsheehan/status/766730925287747584">August 19, 2016</a></blockquote>
<blockquote class="twitter-tweet" data-conversation="none">
<p dir="ltr" lang="en"><a href="https://twitter.com/kinlane">@kinlane</a> so i love this idea but i will probably never have a no-signup-required service again</p>
&mdash; John Sheehan (@johnsheehan) <a href="https://twitter.com/johnsheehan/status/766730874612092933">August 19, 2016</a></blockquote>
<blockquote class="twitter-tweet" data-conversation="none">
<p dir="ltr" lang="en"><a href="https://twitter.com/kinlane">@kinlane</a> pretty sure the example from your post could be used as an open proxy (like hurl.it was before recaptcha)</p>
&mdash; John Sheehan (@johnsheehan) <a href="https://twitter.com/johnsheehan/status/766731066862206977">August 19, 2016</a></blockquote>
<script src="http://platform.twitter.com/widgets.js"></script>
<p>Definitely, something to consider. In the current online environment, it might become quite a pain in the ass to maintain an anonymous app, as John points out. This is one reason I work to publish <a href="http://apievangelist.com/2013/09/24/excel-and-csv-conversion-to-json-and-xml-in-javascript-that-runs-100-on-github/">my API tooling as standalone JavaScript applications</a>, which run 100% on Github. First off they run on Github infrastructure, and use Github's bandwidth. Second, this type of app is forkable, and people can choose to run them wherever they desire--on Github, or any other site they wish.</p>
<p>I'll keep an eye out for other anonymous apps built on top of API service providers, or individual APIs--maybe there are other successful models out there, or maybe there is also some other cautionary tales we should hear.</p>