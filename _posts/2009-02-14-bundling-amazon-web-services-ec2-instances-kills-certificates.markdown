---
layout: post
title: 'Bundling Amazon Web Services EC2 Instances Kills Certificates'
---
Yeah you heard me! Bundling Amazon Web Services EC2 Instances can kill poor innocent SSL certificates.<p></p>
I had it happen the other night...thought I'd bundle all my instances....had done a bunch of configuration changes and thought it would be good idea. When came back up. 6 instances with SSL certs all down.<p></p>
I didn't get into too much detail, but has something to do with the permissions the are entered in the certificate store with. So reinstalling your SSL certificate works.<p></p>
I thought it was because I tried bundling 10 instances at once...or the face that they failed.<p></p>
But I just proved with two separate Amazon EC2 instances and each one did the same thing. Can you please look into this AWS? I try to do bundles of each server after changes / maintenance to keep an AMI of good machine around.<p></p>
It kind of makes a lot of work if I have to re-import each sites SSL with file.