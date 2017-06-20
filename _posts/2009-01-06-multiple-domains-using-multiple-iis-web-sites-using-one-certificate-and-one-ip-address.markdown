---
layout: post
title: 'Multiple Domains using Multiple IIS Web Sites using One Certificate and One IP Address'
---
I haven't researched this one in a while, I am glad I had the chance to research for a new project.<p></p>
I need to be able to setup many sites using a single domain. So each site will be a subdomain within this chose domain.<p></p>
I have always used one web site on Windows Server because I would need multiple IP Addreses and SSL certificates. I had research the wildcard certificates a couple of times, but the multiple IP address need always trumped. IP Addresses aren't as cheap as they used to be. I remember paying $5.00 / month for a whole C Block.<p></p>
So tonight I was researching and I came across <a title="Wildcard SSL Certificates from Digicert" href="http://www.digicert.com" target="_blank">Wildcard SSL Certificates from Digicert</a>. They rock!! Their process is easy and smooth. I highly recommend them.<p></p>
Then I saw as one of their features is you could do multiple sites with one IP Address on IIS 6.0. Something I have been asking for for a while.<p></p>
Then I found this page on how to do it on IIS and Apache - <a href="http://www.sslshopper.com/article-how-to-configure-ssl-host-headers-in-iis-6.html">http://www.sslshopper.com/article-how-to-configure-ssl-host-headers-in-iis-6.html</a><p></p>
Good stuff....really enjoy the discovery and changes I find on a daily basis.