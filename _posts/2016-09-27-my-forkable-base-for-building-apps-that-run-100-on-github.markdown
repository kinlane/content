---
layout: post
title: 'My Forkable Base For Building Apps That Run 100% On Github'
---
<h1>Github Micro Tool</h1>
<p>Github provides a very powerful platform for developing applications. When you use the base Github functionality, in conjunction with Github Pages, and the Github API--some pretty interest approaches to application deployment emerge.</p>
<p>I learned this approach from <a href="https://developmentseed.org/">Development Seed</a> while working with the White House to open up data across federal government agencies, but is an approach I have evolved, and improved upon while developing what I am going to call Github micro tools.</p>
<p>My Github micro tools run 100% on Github, using <a href="https://pages.github.com/">Github Pages</a> as the front-end, the&nbsp;Github repo as a backend, and the <a href="https://developer.github.com/v3/">Github API</a> as the communication between--with Github OAuth as the security broker of who can put the application to work.</p>
<p>I needed to use this approach across several different micro tools, so I thought I'd <a href="http://kinlane.github.io/github-micro-tool/">create a base template that I can use as forkable base for these tools I'm building</a>, while also sharing the approach with others.</p>
<h2>Apps Running 100% On Github</h2>
<p>I like my apps like my APIs--small and reusable. Building applications that run entirely on Github&nbsp;makes sense to me because it is focused on developing apps that anyone can fork and put to use under their own account--relying on Github to do all the heavy lifting, and cutting out the middleman (me). Each micro tool runs as a Github repository, which comes with all the benefits of Github like versioning, social coding, issue management and much more. You can <a href="https://github.com/kinlane/github-micro-tool">fork my project on Github, and begin using within your Github user account or orgnization</a>.</p>
<h2>Github Pages As Application Front-End</h2>
<p>One of the interesting features Github provides with each repository is the ability to launch a simple static site using <a href="https://pages.github.com/">Github Pages</a>. I use these static project sites to run all my API project and is something I have been evolving it to be a front-end for this approach to providing micro tools. Github pages provide&nbsp;a simple place to put al my applications, where I can store and manage in a very static, secure, and stable way (well the security and stability is offloaded to Github).</p>
<h2>Static Jekyll Application Front-End</h2>
<p><a href="https://jekyllrb.com/">Jekyll</a> provides a simple, static way to help tame the front-end of the applications I am building. The static content management system provides tools for managing the look and feel of each application, the pages within, and allow me to have a blog if I want. Additionally, Jekyll provides a YAML and JSON core, which when combined with <a href="https://shopify.github.io/liquid/">Liquid</a> and JavaScript, opens up to some pretty interesting opportunities for building applications.</p>
<h2>Github API As An App Connector</h2>
<p>With the base of an application, I am using the <a href="https://developer.github.com/v3/">Github API</a> as the connector for reading and writing data and content to the base Github repository for this application, in addition to relying on the native features available in Jekyll, and Liquid. The API allows any application to access its underlying data store when a user is properly authenticated using a <a href="https://github.com/settings/tokens">Github personal OAuth token</a>.</p>
<h2>Github OAuth for Authentication</h2>
<p>To allow this application interaction to securely occur I am relying on Github OAuth as the gatekeeper. For this example, <a href="https://github.com/settings/tokens">I am using a Github personal tokens retrieved from within any Github account</a>, instead of using a proxy or service like <a href="http://OAuth.io">OAuth.io</a> because I want this solution to be forkable and self-contained. Your tokens will not give you access to this application when it exists under my Github account, but if you fork it, your tokens will give you access to only your forked version. All you do is pass a token into this page using ?token=[your token here], and the API will allow for writing to the underlying repository.</p>
<h2>Cookie.js To Store The OAuth Token</h2>
<p>Once the OAuth token is passed into the URL I use <a href="https://github.com/ScottHamper/Cookies">cookies.js</a> to store the token for use across all potential pages of a micro tool. This approach helps prevent it being included in any links and passed between pages. Once each cookie expires, the user is required to pass another valid token in through the URL to set the cookie again, opening up API access to the applications backend. This&nbsp;project is meant to be interactive, and you can validate there is a token here:</p>
<ul>
<li><a href="#">Check If Token Exists</a></li>
</ul>
<h2>Github.js To Communicate With API</h2>
<p>With a valid OAuth token, I use <a href="https://github.com/michael/github">Github.js</a> as the client side JavaScript client for interacting with the Github API. While Github.js allows for using almost all available API endpoints, most application functionality will be just about reading and writing YAML and JSON files using repository paths. For most of the application functionality, I will rely on Liquid for reading YAML and JSON data, and Github.js for writing of data to the underlying repo using the Github API. If you have a valid Github OAuth token passed in and have access to the Github repository for this application, you can click below to see if it will successfully write:</p>
<ul>
<li><a href="#">Check If We Can Write To Repo</a></li>
</ul>
<h2>Forkable Base For Apps That Run 100% On Github</h2>
<p>I hope this provides a base project that demonstrates what is possible when you build applications on top of Github. I am going to fork it and build another prototype that reads and writes to a YAML file in the _data folder for the underlying repo, exploring what is possible when it comes to using Github as a data-driven micro tool platform.</p>
<p>The code that makes this happen is pretty simple, and the Github repository is meant to be pretty self-contained, and here are list of technologies at play here:</p>
<ul>
<li><a href="https://github.com/">Github</a></li>
<li><a href="https://pages.github.com/">Github Pages</a></li>
<li><a href="https://jekyllrb.com/">Jekyll</a></li>
<li><a href="https://shopify.github.io/liquid/">Liquid</a></li>
<li><a href="https://developer.github.com/v3/">Github API</a></li>
<li><a href="https://github.com/settings/tokens">Github Personal Access Tokens</a></li>
<li><a href="https://github.com/ScottHamper/Cookies">Cookies.js</a></li>
<li><a href="https://github.com/michael/github">Github.js</a></li>
</ul>
<p>You can find the front for this app at <a href="https://kinlane.github.io/github-micro-tool/">kinlane.github.io/github-micro-tool/</a>, and <a href="https://github.com/kinlane/github-micro-tool">the repo behind this project over at my Github account</a>. Have fun, and <a href="https://github.com/kinlane/github-micro-tool/issues">feel free to submit any issues if you have any questions or comments</a>.</p>