---
layout: post
title: 'Read It Later Binder with Instapaper and Mimeo Connect'
---
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/instapaper.png" alt="" width="125" align="right" />I do a lot of reading on topics ranging from APIs to Printing. I read articles, white-papers and other news from a wide variety of sources on my desktop, laptop, tablet and my mobile phone.<p></p>
When I come across longer articles I tend to save them for reading later, using a tool called <a title="Instpaper" href="http://www.instapaper.com">Instapaper</a>.
<div><p></p>
<span>With a single click, Instapaper allows me to save an article from any web page, and read it later. I can do this from any of my computers, tables or IPhone. Then when ready I can go to my Instapaper account, in my browser or using my IPhone or IPad application and read the post in its entirety.</span><p></p>
<span>This type of read it later format has replaced my Sunday Paper. I tend to sit down on Saturday and Sunday mornings and read the longer pieces I didn't have time for during my busy week.</span><p></p>
<span>This type of reading material is well suited for my IPad, but this isn't always the perfect tool for other readers. Some people would prefer having in a printed format to take wherever they go, and be completely offline. </span><p></p>
<span>Last week I came up with the idea for a <a title="Friday Read it Later Binder with Instapaper" href="../../projects/idea_detail.php?ID=13">Friday read it later binder with Instapaper</a>. This week I made that idea a reality. I put together a prototype of what this could look like using three separate APIs:</span>
<ul class="mainlist">
	<li><strong><a title="Instapaper API" href="http://www.instapaper.com/api/full">Instapaper API</a></strong> - I pull all my unread bookmarks from Instapaper using their API. Instapaper requires you have a full account for this functionality, but it costs $12 / year. Definitely worth it.</li>
	<li><strong><a title="PDF Crowd API" href="https://pdfcrowd.com/html-to-pdf-api/">PDF Crowd API</a></strong> - Once I have all the latest bookmarked articles, papers, etc from Instapaper I use PDF Crowd to create a PDF from them.</li>
	<li><strong><a title="Mimeo Connect Cloud Print API" href="../../">Mimeo Connect Cloud Print API</a></strong> - Using Mimeo Connect I take the PDF I've created, pass the URL to the REST API along with the document ID for the type of binder or binding I want. I pass the API my shipping addres, get the shipping options returned, and place order for my binder.</li>
</ul>
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo/mimeo_connect_logo.jpg" alt="" width="175" align="right" /><span>Using Instapapers powerful suite of bookmarking tools and three separate APIs I can produce a binder or booklet of articles, white-papers and other news from the week for easy reading over the weekend.</span><p></p>
<span>If I get this in by Thursday night I can have the printed copy on my desk Friday before I leave for the weekend. In the northeast same day shipping is even possible.</span><p></p>
<span>You can download the <a title="PHP Code for this at Github" href="https://github.com/mimeoconnect/InstapaperBinder">PHP code for this prototype at Github</a>, and build your own read it later application using Mimeo Connect.</span><p></p>
</div>
&nbsp;
<h6 class="zemanta-related-title" style="font-size: 1em;">Related articles</h6>
<ul class="zemanta-article-ul">
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/06/instapaper-full-api-with-xauth-php-class/">Instapaper Full API with XAuth - PHP Class</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://www.kinlane.com/2011/05/read-it-later-binder-using-instapaper/">Read It Later Binder Using Instapaper</a> (kinlane.com)</li>
	<li class="zemanta-article-ul-li"><a href="http://blog.apievangelist.com/2011/04/28/instapaper-mobile-app-and-api-strategy/">Instapaper Mobile App and API Strategy</a> (apievangelist.com)</li>
</ul>
