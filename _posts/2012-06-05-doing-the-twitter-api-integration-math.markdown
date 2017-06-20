---
layout: post
title: 'Doing the Twitter API Integration Math'
---
<p><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/twitter/twitter-full-logo-black.png" alt="" align="right" /></p>
<p>I&rsquo;m expanding the <a title="API Evangelist" href="http://www.apievangelist.com">API Evangelist</a> network.  I&rsquo;ve recently taken down the API area of API Evangelist, and launching under the brand API stack. &nbsp;Then I&rsquo;m formalizing some aspects of my API industry monitoring in two areas:</p>
<ul class="mainlist">
<li><strong>API Ranking</strong> - I&rsquo;ve developed a decent algorithm for ranking APIs, and I want to do it regularly, in real-time</li>
<li><strong>API Monitoring</strong> - Real-time monitoring and analysis of APIs their blogs, twitter accounts and Internet sentiment about APIs</li>
</ul>
<p>One aspect of this work is using Twitter to monitor and rank the API landscape with the following data points:</p>
<ul class="mainlist">
<li><strong>APIs Twitter Accounts</strong> - Pull all the tweets in real-time for 900+ APIs I&rsquo;m watching</li>
<li><strong>API @Mentions</strong> - Pull all the @mentions for APIs in real-time for the 900+ APIs I&rsquo;m watching Industry Keyword</li>
<li><strong>Industry Monitoring</strong> - Monitor 80+ keywords I&rsquo;m watching, pulling tweets searches for these</li>
<li><strong>Service Providers - </strong>Pull all the Tweets for an average of 5 Twitter accounts for each of 20 service providers, @mentions for those account  plus keyword searches for their business name</li>
<li><strong>Hackathons</strong> - Pull Tweets for about an average of 50 hackathons per month, plus the #hashtags for each of those events as well</li>
</ul>
<p><img style="padding: 25px;" src="http://kinlane-productions.s3.amazonaws.com/calculus.png" alt="" width="250" align="right" /></p>
<p>In short, I need to pull quite a few Tweets from quite a few different Twitter API searches and Twitter user accounts.  The velocity (number of tweets sent) for each of these data points can vary.  As some APIs are only Tweeting once or twice a week, while some are well....the Twitter API account with quite a few tweets as well as numerous @mentions.</p>
<p>It&rsquo;s really impossible to know what volume I&rsquo;m going to be pulling each hour, but I guess I&rsquo;m going to figure out pretty quickly.  To begin pulling Tweets, I acknowledge I have three optons:</p>
<ul class="mainlist">
<li><strong><a title="Twitter REST API" href="https://dev.twitter.com/docs/api">Twitter REST API</a> -</strong> Pull directly from the public Twitter REST API</li>
<li><strong><a title="Twitter Streaming API" href="https://dev.twitter.com/docs/streaming-apis">Twitter Streaming API</a> -</strong> Pull using the public Twitter Streaming API</li>
<li><strong><a title="Twitter Resellers" href="/admin/blog/Twitter Resellers">Twitter Resellers</a> (<a title="Gnip" href="http://gnip.com/twitter">Gnip</a> and <a title="Datasift" href="http://datasift.com/">Datasift</a>) -</strong> Approach each of the two partners and understand the scope and costs involved</li>
</ul>
<p>First let&rsquo;s talk about pros and cons of each source for Twitter data:</p>
<ul class="mainlist">
<li><strong>Twitter REST API - </strong>Pro: Free access, I&rsquo;m also allowed to re-display the Tweets.  Con:  150 unauthenticated / 350 authenticated requests per hour per IP address</li>
<li><strong>Twitter Streaming API - </strong>Pros: Tweets come in real-time.  Cons:  &ldquo;All accounts may access the statuses/sample and statuses/filter methods at default access levels. Accounts may also be granted broader data access on these same methods on a case-by-case basis. Access to other methods requires a special arrangement with Twitter. Contact Contact Twitter with your use case, a brief description of your organization, and the requested access level(s).&rdquo;  OK not sure what that means??   And bonus, it never exceeds 1% of fulll Twitter firehose.</li>
<li><strong>Twitter Resellers - </strong>Pros:  Potentially access 50% of full firehose, and more reliable access &nbsp;Cons:  Costs a lot of $$ + .10 per 1000 tweets for licensing through them, and can&rsquo;t redisplay any Tweets</li>
</ul>
<p>I talked about the <a title="self-service vs. sales oriented approaches of Datasift vs. Gnip" href="http://blog.apievangelist.com/2012/06/01/self-service-vs-sales-oriented-web-apis/">self-service vs. sales oriented approaches of Datasift vs. Gnip</a> the other day, so I&rsquo;m still figuring out scope and costs here.  With Gnip its the hurry up and wait enterprise sales approach and with Datasift I have to figure out how to setup the proper streams, and how much work I can get done for one of their DPU (Data Processing Unit).</p>
<p><a title="Gnip" href="http://gnip.com/twitter"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/gnip/gnip-logo.jpg" alt="" width="150" align="right" /></a></p>
<p>50% of my Twitter usage will be analytical vs other 50% be display, meaning I will be making ranking and monitoring decisions programmatically rom the Twitter data, but I would also like to show Tweets on the detail pages for APIs, Hackathons and Service providers.  I do this currently for Hackathons, but APIs and Service Providers it will be a new thing.   So immediately I&rsquo;m faced with a business decision.  The only way I can get Tweets if I want to display is via Twitter public API--if I get through Gnip or Datasift I can&rsquo;t display them.</p>
<p>I&rsquo;m left with using Twitter REST API or Streaming API to get what I need.  Now my concern is rate limits.  I am doing a lot of predictive math to understand what my Twitter API consumption will be, to understand what my plan of attack will be.  I will have to use multiple machines to scale this as to expand my public facing IP exposure to Twitter--this will be costly.  I&rsquo;m exploring using <a title="Iron.io" href="http://www.iron.io/">Iron.io</a> as a possible solution for handling my jobs.</p>
<p><a title="Datasift" href="http://datasift.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist/datasift/datasift-logo.png" alt="" width="200" align="right" /></a></p>
<p>Since I really want to be able to display Tweets, I will be starting with the Twitter API.  But I will also figure out scope and costs for Gnip and Datasift simultaneously.  But this process has really taken the joy out of my project.  I would much rather be hacking a way, building my monitoring and ranking system, then either via my own dashboard or something Twitter should be providing, understand my API consumption. Then I&rsquo;d be very happy to pay for that usage to save me the headache and time I&rsquo;m going through. &nbsp;Ok, back to reality. &nbsp;</p>
<p>Now that I&rsquo;ve done my basic Twitter API integration math, now for a little more work on hacking together the solution to pull from Twitter public API, crank it up to high gear and see where I start hitting the API rate limits--and since there is no <a href="/admin/blog/relief valve from Twitter for API rate limiting">relief valve from Twitter for API rate limiting</a>, I will have to create my own relief valve or make other decisions, like having to use Gnip or Datasift.</p>