---
layout: post
title: 'Separating The Layers Of The API Operations Onion While Thinking About API Copyright'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-onion.png" alt="" width="250" align="right" /></p>
<p>I'm continuing my trek through my recent notes, and engaging in more conversations with knowledgeable folks, on the topic of API copyright. One recent conversation was with <span>Mike Linksvayer (</span><a href="https://twitter.com/mlinksva">@mlinksva</a><span>), who pointed me to his very informative&nbsp;</span><a href="http://gondwanaland.com/mlog/2014/05/29/api-commons/">blog post, where he discusses API copyright</a><span>.</span></p>
<p>In addition to his thoughts on <a href="http://apivoice.com/2014/06/06/implementation-of-an-api-design-should-never-require-permission-from-the-api-designer/">why you should never have to ask permission to use an API design from its designer</a>, Mike quantified what I'd consider to be the API operations onion, allowing us to think about where not just copyright can apply, but patents, and potentially other licensing approaches:</p>
<ul class="mainlist">
<li>API Specification</li>
<li>API Documentation</li>
<li>API Implementations, Server</li>
<li>API Implementations, Client</li>
<li>Material (often &ldquo;data&rdquo;) made available via API</li>
<li>API metadata (e.g, as part of API directory)</li>
</ul>
<p>I would add in data model, something you should also consider what type licensing may apply. Mike goes on to state that:</p>
<blockquote>
<p><em>"1-4 are clearly works subject to copyright, while 5 and 6 may or may not be (e.g., hopefully not if purely factual data). Typically only 3 and 4 might be restricted by patents.&rdquo;</em></p>
</blockquote>
<p>Which I definitely agree with, but also aware that there are other licensing considerations for code, and separate discussions around how to license your data or its data model.  While working on <a href="http://apicommons.org">API Commons</a>, I'm focusing on applying either CC-BY or preferably CC0 to the API design. While I encourage everyone to critically think about what type of code license to apply to server and client side code, and to your data, the fight I'm picking is specifically around applying copyright to API specifications, and keeping them as open and interoperable as possible.</p>
<p>Mike&rsquo;s <a href="http://gondwanaland.com/mlog/2014/05/29/api-commons/">post on API commons</a> has given me a lot of material to think about, as well as someone with a lot of experience on the subject to talk to during this ongoing discussion around API copyright. This is not an issue that will be decided overnight, even with the upcoming &ldquo;fair use&rdquo; judgement remaining in the Oracle v Google case, and I need as many smart people as I can to ally myself with, as I work to make sense of all of this.</p>