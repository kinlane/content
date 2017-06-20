---
layout: post
title: 'Twitter Launches New, Not So Open Graph, aka Twitter Cards'
---
<p><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/twitter/twitter-dave-winer.gif" alt="" width="250" align="right" /></p>
<p>I woke up this morning to Dave Winer&rsquo;s post, <a href="http://scripting.com/stories/2012/06/13/twittersLevelPlayingField.html">Twitter's (not) level playing field</a>, in my feed.  Where Dave is trying to understand the logic of what content goes into the "detail" pane of a Tweet.  At first glance it looks purely like Twitter is supporting&nbsp;<a href="http://oembed.com/">oEmbed</a>, then from looking at the code of some of their partners it appears to be an <a href="http://ogp.me/">Open Graph</a> implementation.</p>
<p>Then after running some tests it appears that Twitter supports oEmbed and Open Graph in this pane when it comes to rich media.  But after looking through some of their new partner sites I started noticing a new set of OpenGraph-esque tags:</p>
<p>I did plenty of searches for this new tagging structure with no results.  Then a few moments ago I came up with a new page for <a title="Twitter Crds" href="https://dev.twitter.com/docs/cards">Twitter Cards</a>:</p>
<p style="padding-left: 30px;"><em>Twitter cards make it possible for you to attach media experiences to Tweets that link to your content. Simply add a few lines of HTML to your webpages, and users who Tweet links to your content will have a "card" added to the Tweet that&rsquo;s visible to all of their followers.</em></p>
<p><img style="padding: 15px; display: block; margin-left: auto; margin-right: auto;" src="http://kinlane-productions.s3.amazonaws.com/twitter/twitter-cards-1.png" alt="" width="500" /></p>
<p>There are 3 card types that can be attached to Tweets, each of which has a unique consumption experience built for Twitter's web and mobile clients:</p>
<ul class="mainlist">
<li><strong>Summary -&nbsp;</strong>The default card, which includes a title, description, thumbnail image, and Twitter account attribution.</li>
<li><strong>Photo</strong> - A Tweet sized photo card.</li>
<li><strong>Player</strong> - A Tweet sized video/audio/media player card.</li>
</ul>
<p>You can specify the type of card for your content by adding the following HTML to the HEAD section of your page:</p>
<p><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/twitter/twitter-card-2.png" alt="" width="300" align="right" /></p>
<p>Twitter cards looks like they have taken a page out of the Facebook Open Graph playbook, and taken an existing open protocol and used it for a not so open use.  Twitter Cards will only render for domains which have been whitelisted by Twitter, and if you would like your domain to be considered for inclusion in the whitelist, you have to <a href="https://dev.twitter.com/form/participate-twitter-cards">fill out a form</a>--and Twitter clearly states that "they will not be able to respond to or approve all requests".</p>
<p>The move to support an open graph style protocol definitely makes sense to me, but not including developers in this early on, doesn&rsquo;t.  I also find it interesting that they <a href="http://blog.twitter.com/2012/06/experience-more-with-expanded-tweets.html">don&rsquo;t reference Twitter Cards in their announcement today on the main Twitter blog</a>?  I guess a <a href="https://dev.twitter.com/blog">Twitter Dev Blog</a> announcement is forthcoming?</p>