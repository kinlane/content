---
layout: post
title: 'Twitter API Integration Math: REST API'
---
<p><img src="http://kinlane-productions.s3.amazonaws.com/twitter/twitter-bird-blue-on-white.png" alt="" width="200" align="right" /></p>
<p>I talked yesterday about the <a title="Twitter API Integration I'm doing for my API ranking and monitoring system" href="/2012/06/05/doing-the-twitter-api-integration-math/">Twitter API integration I&rsquo;m doing for my API Evangelist ranking and monitoring system</a>.  Long story short is I&rsquo;m trying to get a large volume of Tweets from a large number of Twitter accounts for use in my ranking and monitoring algorithm, and for display on API, service provider and hackathon detail pages.</p>
<p>Last night I started pulling Tweets for just one of my data points:  Twitter accounts of 900+ APIs.</p>
<p>Using the <a title="Twitter REST API" href="https://dev.twitter.com/docs/api">Twitter REST API</a>, I&rsquo;m allowed to make 350 authenticated calls per hour, with each call I can get 200 Tweets.  Using the Twitter <a href="https://dev.twitter.com/docs/api/1/get/statuses/user_timeline">statuses/user_timeline</a>, I am pulling an average of 1000 tweets per user.  So each user is approximately 5 calls, and I was able to process 70 APIs before I hit my limit.</p>
<p>With 830 more API Twitter handles to process, one can quickly see that the REST API will not get me what I need.  I would need to run 13 separate servers to be able to get my Twitter data for the APIs.  And this is just one of my data points.</p>
<p>As Taylor Singletary (<a title="@episod" href="https://twitter.com/#!/episod">@episod</a>) from Twitter tweeted this morning:</p>
<blockquote class="twitter-tweet">
<p>@<a href="https://twitter.com/kinlane">kinlane</a> You'll likely get by just fine with just Streaming API's filter/follow. It takes a lot of tweets to encompass 1% of the firehose.</p>
&mdash; Taylor Singletary (@episod) <a href="https://twitter.com/episod/status/210400888928481281">June 6, 2012</a></blockquote>
<script src="http://platform.twitter.com/widgets.js"></script>
<p>The Twitter REST API will not provide the access I need, and deliver the data I need for my API ranking and monitoring system.  So next step is to write code that uses the <a href="https://dev.twitter.com/docs/streaming-apis">Twitter Streaming API</a>, and see what kind of access it provides me for my startup.</p>