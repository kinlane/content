---
layout: post
title: 'Email in the Amazon Cloud Part 4 - TrendMicro Maps'
---
I woke up one morning and got an email from a project manager. The original email from a client had a returned email with the following email server response:
<div style="margin-left: 40px;"><em>Remote server replied: 550 5.7.1 ... Mail from xxx.xxx.xxx.xxx blocked using Trend Micro <a class="zem_slink" title="DNSBL" rel="wikipedia" href="http://en.wikipedia.org/wiki/DNSBL">RBL</a>+. Please see http://www.mail-abuse.com/cgi-bin/lookup?ip_address=xx.xxx.xxx.xxx</em></div>
We were black listed. So I went to their removal page, entered my <a class="zem_slink" title="IP address" rel="wikipedia" href="http://en.wikipedia.org/wiki/IP_address">IP address</a> and waited. Later that day I get an email from them:
<div style="margin-left: 40px;"><em>xxx.xxx.xxx.xxx</em><em> is listed on the <a class="zem_slink" title="Dialup Users List" rel="wikipedia" href="http://en.wikipedia.org/wiki/Dialup_Users_List">DUL</a> because it is not defined in rDNS
as static or dynamic. Upon checking, here is the rDNS:</em><p></p>
<em> </em><em>xxx.xxx.xxx.xxx</em><em> (ec2-1</em><em>xxx.xxx.xxx.xxx</em><em>.compute-1.amazonaws.com)</em><p></p>
<em>You will need to work with your ISP to correctly define the IP, then ask them to contact us at</em><p></p>
<em>dul@mail-abuse.com</em><p></p>
<em>Then we can work with the ISP to resolve the issue and remove your IP.</em><p></p>
</div>
They put the responsibility on Amazon to get the IP address de-listed, since they owned it. So after doing much research I found that this same problem had happened with <a href="http://www.google.com/url?q=http%3A%2F%2Fsearchcloudcomputing.techtarget.com%2Fnews%2Farticle%2F0%2C289142%2Csid201_gci1371369%2C00.html&amp;sa=D&amp;sntz=1&amp;usg=AFrqEzdG-Y8TUo-vQlx1qOjatgy_cc8yTQ">SpamHaus</a>. Since so many spammers are also taking advantage of the cloud, top SPAM black lists were just blocking entire Amazon IP blocks. Not taking into considering the hundreds or thousands of valid Amazon Web Services customers sending email legitimately.<p></p>
I can understand that spammers are a problem and that black lists have value in the SPAM game. However I viewed this as an attack on <a class="zem_slink" title="Cloud Computing" rel="wikinvest" href="http://www.wikinvest.com/concept/Cloud_Computing">cloud computing</a>. Everyone I talked to about the situation from TrendMicro to SAP IT in Germany all said the same thing. Why don't you just use a real infrastructure that isn't in the cloud. They just dismissed the cloud as the problem.<p></p>
Trend Micro decided to just list the entire Amazon blocks rather than listing individual offenders.<p></p>
So I needed to just wait for Amazon to do something or <a href="http://www.mail-abuse.com/">Trend Micro MAPS</a>. So I just started lobbying both sides. Heavily!<p></p>
They both pointed the finger at the other side. I escalated my ticket with <a href="http://aws.amazon.com/">Amazon Web Services</a> and emailed <a href="http://www.mail-abuse.com/">Trend Micro MAPS</a> on a daily basis asking them to not hold our business hostage any more.<p></p>
Then I got a response on my <a href="http://aws.amazon.com/">Amazon Web Services </a>support ticket one day about <a href="http://www.kinlane.com/?p=1104"><span class="zem_slink">reverse DNS</span> on our IP addresses</a>.
<p style="text-align: center;"><strong>Email in the Amazon Cloud</strong> - <a href="../?p=1095">Part 1</a> - <a href="../?p=1098">Part 2</a> - <a href="../?p=1100">Part 3</a> - <a href="../?p=1102">Part 4</a> - <a href="../?p=1104">Part 5</a> - <a href="../?p=1106">Part 6</a> - <a href="../2010/07/email-infrastructure-in-the-amazon-cloud/">Guide  to Email in the Amazon Cloud</a><p></p>
