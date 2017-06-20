---
layout: post
title: 'Local Places Data Using CityGrid with Hyp3rL0cal'
---
<a title="CityGrid APIs" href="http://developer.citygridmedia.com/" target=""><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/citygrid/citygrid_logo.jpg" alt="" width="250" align="right" /></a>I needed to learn more about the<a title="CityGrid APIs" href="http://developer.citygridmedia.com/" target="">CityGrid APIs</a>. What better way than to actually build a prototype.<p></p>
I thought it would be good to have a <a title="simple local business directory" href="http://hyp3rl0cal.com/index.php">simple local business directory</a> that could be deployed all by itself, or as part of another web site.<p></p>
I wanted the directory to look good, but I didn't want to do any graphic design, so I used<a href="http://twitter.github.com/bootstrap/">Twitter Bootstrap</a>for the user interface (UI).<p></p>
I put together five pages, allowing you to browse some local business categories in West Hollywood, CA.<a title="Hyp3rL0cal" href="http://hyp3rl0cal.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/hyp3rl0cal/Hyp3rL0cal-3.png" alt="" width="350" align="right" /></a>
<ul class="mainlist">
	<li>Home</li>
	<li>About</li>
	<li>Search</li>
	<li>Detail</li>
	<li>Contact</li>
</ul>
The site doesn't use a database. You set the sites config file to a city and state, it makes calls to the<a title="CityGrid APIs" href="http://developer.citygridmedia.com/" target="">CityGrid APIs</a>in real-ime, with the latest business listings, images, offers and reviews.<p></p>
The site is providing a way for me to learn about the <a title="CityGrid APIs" href="http://developer.citygridmedia.com/" target="">CityGrid APIs</a>, while also producing usable code that other developers can use to bootstrap their own hyperlocal sites and applications.<p></p>
This project is still in development, you can<a href="https://github.com/kinlane/CityGrid---Local-Directory" target="_blank">download it at Github</a>.<p></p>
I will work on other enhancements to this prototype, but first I'd like to create a ruby and python version of Hyp3rl0cal, so it can be used as a base for CityGrid API development.<p></p>
Lot's of learning ahead, I will keep publishing my code to Github and link everything at <a title="Hyp3rL0cal" href="http://hyp3rl0cal.com/">Hyp3rL0cal</a>.<p></p>
&nbsp;