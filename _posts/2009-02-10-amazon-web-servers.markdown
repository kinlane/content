---
layout: post
title: 'Amazon Web Servers'
---
I really love the Amazon Web Services platform. It brings some really valuable tools to the table for deploying a companies infrastructure.<p></p>
However there are some areas that really can throw you for a loop.<p></p>
I create bundles and then ultimately AMIs from my core instances. It makes it so I can restore to last nights complete server if I want...with settings and all.<p></p>
I do individual bunlidng then AMI creation of instances all the time. Tonight I thought....oh I will go ahead and do all 10 instances at once.<p></p>
So about midnight all the bundles error out because of Amazon S3 permissions. When all my instances come back up...they all work fine...except for SSL / HTTPS / Port 443.<p></p>
DOH!! I had to remove all certs and reinstall to get back online.<p></p>
What a pain.....but I recovered....and we learned another tidbit about living in the clouds Amazon style.<p></p>
4:00 AM ...night.