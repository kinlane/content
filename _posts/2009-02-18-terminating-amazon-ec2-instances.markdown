---
layout: post
title: 'Terminating Amazon EC2 Instances'
---
There are many features that operating in the clouds using Amazon EC2 brings to the table.

Although there are two areas that make me so nervous:

1) Terminating an Instance
2) Release IP Address

Now I cover my ass with a rigorous backup process and creating AMI of my key production and development instances.

However still terminating an instance always makes me soooo nervous.  Its just so permanent and when you have large applications depending on databases, file servers, svn servers, etc it makes you queezy to push that button.

Ok...well this is just a Dev server that we upgraded from a 32 bit instance to a 64 bit instance.  I have to kill the 32 bit instance....

Here it goes....