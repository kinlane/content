---
layout: post
title: 'Mimeo Connect Cloud Print API in C#'
---
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/C-Sharp.jpg" alt="" width="125" align="right" /><p></p>
There has been a lot of requests for .NET code samples for integrating applications with the <a title="Mimeo Connect Cloud Print API" href="http://developer.mimeo.com/">Mimeo Connect Cloud Print API</a>.<p></p>
I was telling too many potential customers that I do not have .NET code samples, and they would have to write from scratch.<p></p>
So I finally made time to cranking out a handful of core code samples in C#.  I focused the <a title="Mimeo Print Order Service" href="http://developer.mimeo.com/documentation/service_detail.php?ID=5">Mimeo Print Order Service</a> first, with examples showing how to work with these five methods:
<ul class="mainlist">
	<li><strong><a href="http://developer.mimeo.com/code/code_type_detail.php?ID=63&amp;tag=" target="_blank">NewProduct</a></strong> - Creating a new document template or shell for a new print order</li>
	<li><strong><a href="http://developer.mimeo.com/code/code_type_detail.php?ID=60&amp;tag=" target="_blank">GetItemQuote</a></strong> - Getting a current print quote for a single print product</li>
	<li><strong><a href="http://developer.mimeo.com/code/code_type_detail.php?ID=62&amp;tag=" target="_blank">GetShippingOptions</a></strong> - Get shipping and deliver options for an order</li>
	<li><strong><a href="http://developer.mimeo.com/code/code_type_detail.php?ID=61&amp;tag=" target="_blank">GetOrderQuote</a></strong> - Get a complete quote for an entire print order</li>
	<li><strong><a href="http://developer.mimeo.com/code/code_type_detail.php?ID=64&amp;tag=" target="_blank">PlaceOrder</a></strong> - Place a print order with Mimeo.com</li>
</ul>
These code samples are meant for demonstration.  So they work as is, and may not reflect best practices for a production application environment.  But they provide all the code you will need to make each call against our REST API and print on demand.<p></p>
I will be working on creating more <a title="C# samples for the Mimeo Connect Cloud Print API" href="http://developer.mimeo.com/code/code_type_listing.php?tag=CSharp">C# samples for Mimeo Connect Cloud Print API</a> methods next like print proofing, document, account and address book management in coming weeks.<p></p>
You can get at each code sample by click on the links above, or <a title="complete set at Github" href="PlaceOrder">download the complete set at Github</a>.
