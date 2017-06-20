---
layout: post
title: 'Instapaper Full API with XAuth - PHP Class'
---
<a title="Instapaper API" href="http://www.instapaper.com/api/full"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/instapaper.png" alt="" width="175" align="right" /></a>I'm working my way through a list of projects I have, and currently the<a title="Instapaper API" href="http://www.instapaper.com/api/full">Instapaper API</a> is top of my list.<p></p>
I couldn't find an easy to use PHP class for authenticating against Instapaper's Full API using XAuth.<p></p>
So I downloaded <a title="@abraham" href="http://twitter.com/#!/abraham">@abraham</a> <a title="Twitter OAuth" href="https://github.com/abraham/twitteroauth">Twitter OAuth</a> and stripped out all as much of theunnecessarypieces as I could.<p></p>
I was quickly able to get it up and running authenticating with Instapaper's Full API using<a title="XAuth" href="http://xauth.org/">XAuth</a>.<p></p>
I added two basic methods for:
<ul class="mainlist">
	<li>Listing Instapaper Bookmarks</li>
	<li>Pulling Full Text of Instapaper Bookmark</li>
</ul>
I will add more methods later for other Instapaper API endpoints.<p></p>
One thing you need to know is this is only for full READ / WRITE on the Instapaper API. If you just want to add bookmarks this is not for you, just use the <a title="simple API" href="http://www.instapaper.com/api/simple">simple API</a>.<p></p>
I'm moving to extend this class for <a title="printing read it later binders" href="http://developer.mimeo.com/projects/idea_detail.php?ID=13">printing read it later binders</a> for research and other areas, then I'll come back and add more to this repository.<p></p>
You can <a title="download / checkout on Github" href="https://github.com/kinlane/InstapaperXAuth">download / checkout on Github</a>.
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://blog.programmableweb.com/2011/04/07/instapaper-and-the-concept-of-monetizing-your-api/">Instapaper and the Concept of Monetizing Your API</a> (programmableweb.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/05/read-it-later-binder-using-instapaper/">Read It Later Binder Using Instapaper</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/04/28/instapaper-mobile-app-and-api-strategy/">Instapaper Mobile App and API Strategy</a> (apievangelist.com)</li>
</ul>
