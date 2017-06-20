---
layout: post
title: 'Playing Around With Jekyll Job APIs To Manage My Github Pages'
---
<p><a href="http://jekyllrb.com/"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/github/jekyll-test-tube.png" alt="" width="150" align="right" /></a></p>
<p>I&rsquo;m playing around with a concept right now that I&rsquo;m calling "Jekyll jobs". As you may know, all of my websites use Jekyll, and run on <a href="https://pages.github.com/">Github Pages</a>. Currently I have over 100 separate repos, and managing the content, and data across these repos can get complex.</p>
<p>I use a standardize approach I call &ldquo;<a href="http://hackerstorytelling.com/">hacker storytelling</a>&rdquo; for publishing each of my projects, so I have a handful of things I need to update, ranging from the look of the site, to changes across all Jekyll posts, or pages. To help me keep things orderly and efficient I&rsquo;m considering a lightweight, API driven, jobs framework to help me manage.</p>
<p>I am looking to make many of these &ldquo;jobs&rdquo; available to my girlfriend as well, allowing her to target specific resources, with specific jobs. Some of the jobs I&rsquo;ve outlined are:</p>
<ul>
<li><strong>Link Management - </strong>Help me catalog, and manage the health of links that are used across all blog posts. A lot of links change, go bad, or any other numerous illnesses that occur.</li>
<li><strong>Image Management -</strong> Help me catalog, optimize, and manage images that are used in my blog posts. I&rsquo;m pretty good about manually doing a lot of this, but I sure could use help.</li>
<li><strong>HTML Management -</strong> Sometimes HTML code gets ugly, either because I wrote it and didn&rsquo;t give it the attention it needed, or possibly because it was generated out of another system, either way there is cleanup and maintenance from time to time.</li>
<li><strong>Content Management - </strong>After I write a post I like to constantly re-evaluate tagging, indexing, and providing additional links to related content.</li>
<li><strong>Content Indexing -</strong> My search across all of my Jekyll drive sites is not the best, and I&rsquo;d like a way I can index all, or specific collections, and serve up as simple search API, maybe using ElasticSearch or something.</li>
</ul>
<p>As more of my world runs as small, modular, <a href="http://jekyllrb.com/">Jekyll</a> projects, I&rsquo;m needing a way to run jobs against them, and designing APIs that  do what I need, and use the Github API to work with my Jekyll site content, makes sense. I&rsquo;m thinking I will just pass a Github user, and repo name, as parameters to each Github job API, and have it run a specific task against my _posts folder in the Jekyll install.</p>
<p>Since I&rsquo;m designing these Jekyll jobs as APIs, I can run each one as an API request, and keep the job logic separate from each project. I&rsquo;ll get a couple of these setup, than blog more about the pros and cons of this approach-who knows it may not be what I need to get it done.</p>