---
layout: post
title: 'My Unique Visitors and Page Views For API Evangelist Between Google And CloudFlare'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-analytics-5.jpeg" alt="" width="200" align="right" /></p>
<p>I&rsquo;ve been running all of my websites using <a href="https://www.cloudflare.com/">CloudFlare</a> since this last Thanksgiving weekend. I pointed all of my name-servers for my primary domains like apievangelist.com and kinlane.com to CloudFlare, and I use them manage my DNS, and other related operations of my primary websites.</p>
<p>I&rsquo;m intrigued by the reporting at the DNS level provided by CloudFlare, compared to the reporting at the page level provided by Google Analytics. I&rsquo;ve had Google Analytics installed on all of my websites since I first launched, and use it to establish the estimates for the daily and monthly visitors to my websites&mdash;beyond that I really don&rsquo;t care much about these analytics.</p>
<p>Regardless I think it is interesting to look at CloudFlare numbers for the last 30 days:</p>
<ul>
<li><strong>Regular Traffic:</strong> 112,241 </li>
<li><strong>Crawlers/Bots:</strong> 55,540 </li>
<li><strong>Threats:</strong> 1,697 </li>
<li><strong>Unique Visitors: </strong>34,501 </li>
<li><strong>Page Views: </strong>169,478 </li>
</ul>
<p>Then look at the Google Analytics number for the last 30 days:</p>
<ul>
<li><strong>Sessions: </strong>22,569</li>
<li><strong>Users:</strong> 17,880</li>
<li><strong>Page Views: </strong>38,949</li>
</ul>
<p>Ultimately you can only compare the CloudFlare <span style="text-decoration: underline;">unique visitors</span>, and Google Analytics <span style="text-decoration: underline;">users</span>&mdash;these are the only two numbers that are comparable in my opinion. I don&rsquo;t think CloudFlare removes crawlers/bots from page views, something Google does by default I&rsquo;m assuming&mdash;rendering page views as a very different beast for each service.</p>
<p>I take away two things from this. <strong>1)</strong> How meaningless data points are, unless you believe in them.  <strong>2) </strong>How data points can differ from provider to provider, and at different levels of your architecture. If you ask me what my page views are for API Evangelist, what do I say? You didn&rsquo;t ask me whether it was my CloudFlare or my Google Analytics page views!</p>
<p>When I think about the millions of hours spent in Google Analytics dashboards across numerous industries, and the companies I&rsquo;ve seen spending millions in Adwords for their advertising, all based upon numbers derived from this constructed reality, that we&rsquo;ve collectively bought into&mdash;I am blown away.</p>