---
title: Poor Man Jekyll Post Scheduling
date: 2017-05-17 15:00:00 Z
tags:
- Kin Lane
- Jekyll
- Blog
---

I created a little hack on my Jekyll-driven websites to allow me to publish a week's worth of posts (or more) ahead of time. I've been scheduling these publishing using my homebrew CMS, but I recently ditched it for Siteleaf, and one of the things that were not possible with the CMS was scheduling--so I needed a hack.

I wanted to be able to just publish at least a weeks worth of blog posts, but trickle them out somehow using Jekyll, and not the CMS layer. I got to work publishing a couple of "future" posts and tightening up any holes where the future might leak out into the present--the blog and RSS/Atom listings.

First I set a variable to tell me what the date and time were for any given moment:

{% capture nowunix %}{{'now' | date: '%s'}}{% endcapture %}

Then I translated the publish date for each post into the same format as my definition for now (seconds):

{% capture posttime %}{{post.date | date: '%s'}}

Then you just check to make sure each blog post being display using LIquid is truly in the past:

{% if posttime < nowunix %}[..]{% endif %}

Voila, a filter for the future on my blog listing page, and the RSS or Atom feeds. After this, I published a schedule.xml feed which showed all my blog posts, even for the future. I use this to schedule Tweets, and other social media posts for my blogs throughout the week--allowing my social media management tooling to see into the future when it comes to my blogs.

It is a poor man hack for a blog schedule, but it works. It allows me to schedule my world days or weeks ahead, and stay focused on project work. One of the reasons I abandoned my homegrown CMS is I wanted to be forced to find solutions within the cracks of a variety of SaaS tooling, using feeds and APIs. I feel like these approaches are going to be more valuable to my readers, as I can't expect everyone to deploy a custom solution as I was doing.


