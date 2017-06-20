---
layout: post
title: 'Not All Browsers Are the Same'
---
As part of my 3rd party service development plan for my company I make recommendations for external systems that my company should be using for its operations. We don't buy or develop everything internally. There are some amazing 3rd party applications.<p></p>
A couple notable ones are:
<ul class="mainlist">
	<li>Gmail / Google Apps for Your Domain</li>
	<li>Google Docs</li>
	<li>Google Calendar</li>
	<li>Email Center Pro (ECP)</li>
</ul>
These are applications that I have integrated heavily into our daily operations. Another characteristic they all have is they are heavy JavaScript based applications. One thing I started noticing is my non-tech savvy employees tend to leave these programs open and running all day long. And many will leave their browser open for multiple days with the same application open.<p></p>
Most users are using IE, but a few use Firefox. Memory leaks become a major problem. People's machines slow to a crawl and many times just lock up. I can people complaining and worried applications or their machines.<p></p>
So I started recommending using Google Chrome for their web-based JavaScript application. In initial tests I opened Gmail Personal, Google Docs Personal, Gmail for Google Apps, Google Docs for Apps, and Email Center Pro in both Chrome and Firefox.<p></p>
I left these open all night:
<ul class="mainlist">
	<li>Firefox started at about 50K and grew to 480K by morning.</li>
	<li>Chrome started at about 50K and reduced to 46K by morning.</li>
</ul>
All without usage? I am leaving open all day to see what happens next.