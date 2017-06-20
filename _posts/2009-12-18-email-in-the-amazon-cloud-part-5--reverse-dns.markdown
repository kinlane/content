---
layout: post
title: 'Email in the Amazon Cloud Part 5 - Reverse DNS'
---
I was really excited when I got this email response on my ticket from <a href="http://aws.amazon.com/">Amazon Web Services</a>:<em>
</em>
<div style="margin-left: 40px;"><em>We've reached out to the Amazon EC2 team and here are the next steps. In order for us to proceed, we'll need to setup <a class="zem_slink" title="Domain Name System" rel="wikipedia" href="http://en.wikipedia.org/wiki/Domain_Name_System">DNS</a> <a class="zem_slink" title="NYSE: PTR" rel="stockexchange" href="http://finance.yahoo.com/q?s=PTR">PTR</a> records for EIPs (incl </em><em>xxx.xxx.xxx.xxx</em><em>) under your AWS account. Hence could you provide us with the names you would like to use and the corresponding EIPs (being used for email purposes)?</em><p></p>
<em>I believe the DNS PTR names should match the DNS 'A' records you may currently have resolving to these addresses. Provide us with the name you would like to use and we'll start the process on our end.</em><p></p>
</div>
This was not the response I had expected. I thought either Amazon would negotiate a deal with <a href="http://www.mail-abuse.com/">Trend Micro MAPS</a> to de-list their IP blocks and allow email to be sent or <a href="http://www.mail-abuse.com/">Trend Micro MAPS</a> would back down from the pressure of everyone harassing them.<p></p>
I really didn't think Amazon would start designating reverse DNS for their <a class="zem_slink" title="IP address" rel="wikipedia" href="http://en.wikipedia.org/wiki/IP_address">IP addresses</a>. Even though this is the response that makes the most sense. I just thought they were too large to do this.<p></p>
After some discussion and convincing of them that we were deserving of reverse DNS on 10 IP addresses I got it! I got an email telling me it was done. I did a <a class="zem_slink" title="Reverse DNS lookup" rel="wikipedia" href="http://en.wikipedia.org/wiki/Reverse_DNS_lookup">reverse DNS lookup</a> on all my reserved IP addresses and they reflected my core network domain.<p></p>
I immediately approached <a href="http://www.mail-abuse.com/">Trend Micro MAPS</a> and asked them one more time to de-list my IP addresses. They immediately responded and said it was done.<p></p>
I found my<a href="http://www.kinlane.com/?p=1106"> faith in the cloud</a> coming back.
<p style="text-align: center;"><strong>Email in the Amazon Cloud</strong> - <a href="http://www.kinlane.com/?p=1095">Part 1</a> - <a href="http://www.kinlane.com/?p=1098">Part 2</a> - <a href="http://www.kinlane.com/?p=1100">Part 3</a> - <a href="http://www.kinlane.com/?p=1102">Part 4</a> - <a href="http://www.kinlane.com/?p=1104">Part 5</a> - <a href="http://www.kinlane.com/?p=1106">Part 6</a> - <a href="http://www.kinlane.com/2010/07/email-infrastructure-in-the-amazon-cloud/">Guide  to Email in the Amazon Cloud</a><p></p>
<div id="_mcePaste" style="overflow: hidden; position: absolute; left: -10000px; top: 57px; width: 1px; height: 1px;"><a href="http://www.mail-abuse.com/">http://www.mail-abuse.com/</a></div>
