---
layout: post
title: 'Secure Communication Channels Over Any Network With Telehash'
---
<p><a href="http://telehash.org/"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/telehash/telehash-logo-2.png" alt="" width="250" align="right" /></a></p>
<p>Much like after 911, things will never be the same on the Internet after the Snowden-NSA revelations. Our delusional belief that the Internet is by default &ldquo;open&rdquo;, has been crushed, and corporate and government surveillance is now an expected part of daily life--there is no going back! To help me move forward, I'm exporing possibilities for what is next, which has led me back to a communication protocol called Telehash.</p>
<p>I first learned about <a href="http://telehash.org/">Telehash</a> several years ago, as I was doing the same research on the future of APIs, and in 2014 I&rsquo;m picking up where I lef off with my education. My friend Jeremie is working hard on pushing the communication protocol forward, and e needs help funding his work, as well as attracting active technical contributors&mdash;I am doing what I do best, tell stories around what is possible with Telehash.</p>
<p>There are several key characteristics of Telehash that stand out for me, and make it something I can't get out of my head:</p>
<ul class="mainlist">
<li>Communication channels are <span style="text-decoration: underline;">encrypted all the time</span> - there is no unencrypted mode</li>
<li>Each application instance or device generates its own public/private keypair, they <span style="text-decoration: underline;">cannot be impersonated</span> and security is not dependent on trust in certificate authorities</li>
<li>Network addresses are generated from public key fingerprints, <span style="text-decoration: underline;">not centrally managed as with IP addresses</span></li>
<li>Routing is based on a globally distributed hash table (DHT), <span style="text-decoration: underline;">not a central authority or managed hierarchy</span></li>
<li>Uses a <span style="text-decoration: underline;">dual JSON/binary packet</span> format</li>
<li>Bindings to Bluetooth, IEEE 802.15.4, and other <span style="text-decoration: underline;">low-layer transports</span> are also on the way</li>
</ul>
<p>You see all of the elements of what is needed for a next generation communication protocol in there. This isn&rsquo;t just about privacy and security, it is about us defining our own networks, whether that is on existing Internet infrastructure or adhoc device or an Internet of Things (IoT) defined network.</p>
<p>Telehash is not just some random side project, it is the complete focus of Jeremie (<a href="https://twitter.com/jeremie">@jeremie</a>), who also helped found Jabber/XMPP, which is the backbone of common messaging apps today, including the now infamous WhatsApp that Facebook just acquired for $19B.&nbsp;&nbsp;Telehash is building on what we already know, but introducing the key ingredients we WILL depend on for messaging in the future.</p>
<p>As I did with <a href="http://kinlane.com/2011/02/11/telehash-node-runners-in-egypt/">Telehash Node Runners in Egypt</a>, I&rsquo;m going to continue to craft stories that help us understand how Telehash can be applied, which is already pushing my understanding of what a network can and should be, and how us humans, and our devices can safely communicate on the open Internet, as well as our own privately defined, trusted networks.</p>