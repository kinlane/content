---
layout: post
title: 'Content and Data Management Via Github Pages'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-github.jpg" alt="" width="225" align="right" /></p>
<p>I'm pushing forward how I'm using Github to build prototypes and even full blown applications. I've been publishing all of my public sites using Github + Github Pages for most of the year, but this last week I've taken my usage of Github to new levels.</p>
<p>Using two important JavaScript libraries I'm able to use Github as an application platform in new and exciting ways:</p>
<ul class="mainlist">
<li><strong><a href="https://oauth.io/">oAuth.io</a></strong> - Simple API integration for Github and other providers</li>
<li><strong><a href="https://github.com/michael/github">Github.js</a></strong> - A JavaScript wrapper for the Github API</li>
</ul>
<p>Using oAuth.io I'm able to provide a logon via Github, that is entirely client-side on Github Pages. So there is no server side handling of the oAuth flow(by me), allowing me to authenticate users via Github Pages, securing content behind it in a private repo or allow for editing and saving of content and data live from Github once a user is authenticated.</p>
<p>Using this approach, I'm allowing users to visit an application I have built in HTML, CSS, JavaScript and JSON that is running on Github Pages.  You can choose to authenticate using Github oAuth, and if I have added you to the list of members not the Github organization the repository exists in, you can edit content and data directly from the web page / app.</p>
<p>This is a quick and dirty way to allow a user to manage content via pages and data via JSON using a custom interface I've built and running via Github pages, with no server side technology needed--Github does all of the heavy lifting.</p>
<p>I'm playing with different approaches to giving users control over content and data, allowing them to edit pages and blog posts via apps like prose.io and the ability to edit JSON via JavaScript table editors or using tools like Online JSON Editor.</p>
<p>I'm in the early days of building applications via Github in this way, so I'm sure I will get more sophisticated in my approach in the coming months.  oAuth.io and Github.js has allowed me to move into this new realm and overcome some pretty significant hurdles in how I secure my applications and provide a backend for them that runs exclusively on Github.</p>