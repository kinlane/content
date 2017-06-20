---
layout: post
title: 'Mimeo Connect Print API'
---
I've talked about the <a href="http://www.kinlane.com/2010/10/my-mimeo-future-of-technology-and-printing/">My Mimeo online print and publishing</a>, and the <a href="http://www.kinlane.com/2010/10/my-mimeo-marketplace-creating-a-online-print-store/">My Mimeo Marketplace</a> where you can publish documents for people to purchase.   Now I feel I can actually introduce you to the <a href="http://www.mimeo.com/solutions/mimeo-connect.php">Mimeo Connect Print API</a>, now that you have an overview of Mimeo.<p></p>
Mimeo offers a SOAP Print API as its core enterprise print offering, however my focus with Mimeo is the REST Print API.    The REST API uses basic HTTP Authentication for access your My Mimeo Account, and provides the following services:
<ul class="mainlist">
	<li><strong>Account Service</strong> - Management of your My Mimeo Account(s).</li>
	<li><strong>Document Service</strong> - Access and management of your Mimeo documents assembled in your My Mimeo account.</li>
	<li><strong>Storage Service</strong> - File storage service for various files you use in assembling print documents.</li>
	<li><strong>Proof Service</strong> - Pulling of files from external locations into your My Mimeo library.</li>
	<li><strong>Order Service </strong>- Order of print documents through your My Mimeo account.</li>
	<li><strong>Marketplace Service</strong> - Access, publishing and management of your My Mimeo documents to your My Mimeo Marketplaces.</li>
</ul>
Everything is based upon documents you create within your My Mimeo self-publishing interface.  You can build documents such as binders, book, flyers, posters and more using your My Mimeo account.
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="300" align="right" />
For example, you can create a 20 page booklet complete with cover file, 20 page content files, and a back cover file.  When building your document in My Mimeo you choose all the characteristics of your book from cover, binding, paper, color, etc.  During the process you upload three support files to provide unique content for this book.  One for cover, one for content, and one for back cover.   At any point using the Mimeo Connect REST API Proof Service you can pull new files dynamically from other locations and create new versions of your book document.<p></p>
You can apply the same concept to a single sheet flyer or poster.  You would build your base document in your My Mimeo, then dynamically pull a PDF from any public location and merge with your flyer or poster document, creating an entirely new print document in real-time.<p></p>
Then with the Mimeo Connect REST API Order Service you can generate an order, set how fast you want your order, and the shipping options you want.  It returns a quote that you can use to make ordering decisions from.  Then your printed document arrives on your doorstep at your selected time.<p></p>
Its a pretty interesting approach to print-on-demand, self-publishing, web-to-print or what ever term you wish to use.  It allows you to build base libraries of documents and dynamically generate print orders from these documents, using files uploaded by users of your web applications.<p></p>
I will be spending more time playing with the API over the coming weeks and providing more specific samples of how to build rich web and social applications that take advantage of the REST Print API.