---
layout: post
title: 'Instagram Photo Book [Idea]'
---
<em>This is another post in my <a href="http://www.apievangelist.com/">API</a> Ideas series, I'm posting all my ideas for applications that could be built using the <a href="http://www.mimeo.com">Mimeo</a> Connect <a href="http://www.kinlane.com/category/cloud-computing/cloud-print/">Cloud Print</a> API.</em><p></p>
Instagr.am a popular <a href="http://www.kinlane.com/category/publishing/">Photo</a> sharing <a href="http://www.kinlane.com/category/mobile/iphone/">IPhone</a> applications has become popular among the highly influential IPhone user base.<p></p>
Instagram allows you to take photos on your IPhone apply unique filters to them which change color, brightness, borders and create an entirely new version of your photo.
<img style="padding: 20px;" src="http://kinlane-productions.s3.amazonaws.com/instagram.PNG" alt="" width="250" align="right" />
The mobile app allows you to enhance the average photos taken with your IPhone and quickly share to <a href="http://www.kinlane.com/category/twitter/">Twitter</a>, <a href="http://www.kinlane.com/category/facebook/">Facebook</a>, Flickr or Tumblr.<p></p>
These photos can be very unique, breathing new life into your digital photo taking.<p></p>
The quality of the photos and passion of the user base calls for creation of an Instagram Photo Book tool, allowing users to build photo books online and have them delivered to their homes.<p></p>
A <a href="http://www.kinlane.com/2010/12/instagram-launches-api/" target="_blank">Rogue Instagram API</a> was exposed using the same mechanims the IPhone app uses, but was <a href="http://blog.programmableweb.com/2011/01/12/instagram-shuts-down-third-party-developers-plans-official-api/" target="_blank">quickly shut down by the company</a>.  Without an Instagram API, it makes building a photo book difficult, but not impossible.<p></p>
I was able to pull my photos via my Flickr account.  Using the <a href="http://www.apievangelist.com/api-detail.php?API_ID=116" target="_blank">Flickr API</a> I was able to pull all instagr.am photos using the tag <em>instagram app</em>.<p></p>
Then I was able to assemble the photos onto an HTML page with desired formatting, once formatted I render the HTML to a PDF and send to the Mimeo Connect Cloud Print API Proofing Service.<p></p>
After proofing I'm able to preview my Instagram Photo Book and send to the Mimeo Connect Cloud Print API Order Service and actually order my physical Instagram Photo Book and have it delivered.<p></p>
There is definitely a huge opportunity for some entrepreneur out there to build a Instagram Photo Book Web Application.