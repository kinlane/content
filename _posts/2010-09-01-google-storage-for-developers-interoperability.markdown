---
layout: post
title: 'Google Storage for Developers Interoperability'
---
<img class="alignnone" style="padding: 15px;" title="Google-Developer-Storage" src="http://code.google.com/images/code_labs_logo.gif" alt="" align="right" />I finally got my<a href="http://code.google.com/apis/storage/" target="_blank"> Google Storage for Developers</a> email invite the other day. They promised attendees of Google I/O would get them quicker, it took 3 months.<p></p>
I clicked on the link in my email and requested my keys and logged into the <a href="https://sandbox.google.com/storage/" target="_blank">Google Storage Manager</a>.<p></p>
It has a pretty basic interface for managing your buckets and objects. Just like <a href="../category/amazon/amazon-s3/">Amazon S3</a>.<p></p>
Then I wanted to test out the interoperability of it. Google claims:
<p style="padding-left: 30px;"><strong>Google Storage is interoperable with a large number of cloud storage  tools and libraries that work with services such as Amazon Simple  Storage Service.</strong>
So I downloaded a common <a href="http://code.google.com/p/amazon-s3-php-class/" target="_blank">Amazon S3 PHP Class</a> and changed the request endpoints, request headers, signature identifiers, ACLs, query string parameters and used my Google developer keys.<p></p>
And it work. It listed my buckets I had created through the <a href="Google Storage Manager" target="_blank">Google Storage Manager</a>. I am playing with more to see how I can store files and content at both Amazon S3 and Google Developer Storage.<p></p>
Now to figure out what I will use <a href="http://www.kinlane.com/category/google/google-storage-for-developers/" target="_blank">Google Storage</a> for vs. <a href="http://www.kinlane.com/category/amazon/amazon-s3/">Amazon S3</a>.
