---
layout: post
title: 'New Mimeo Poster Printing API'
---
<a title="Mashape API Platform" href="http://www.mashape.com/"><img src="http://kinlane-productions.s3.amazonaws.com/api-service-providers/mashape-logo.png" alt="" width="200" align="right" /></a>When developers come to<a title="Mimeo Connect" href="http://developer.mimeo.com/">Mimeo Connect</a>, they tend to have one thing in mind--printing from their application. The<a title="Mimeo Cloud Print API" href="http://developer.mimeo.com/">Mimeo Connect Cloud Print API</a>allows you to print a lot of different type of business documents, but usually developers have a specific type in mind.<p></p>
Because of this many developers don't have the time to setup their Mimeo.com accounts, and build the documents they are looking to print. They just want to print. To help address this I am playing around some new ways to deliver printing APIs.<p></p>
Recently I setup a new<a title="Poster Printing API" href="http://www.mashape.com/apis/Poster+Printing+API">Poster Printing API</a>using the<a title="Mashape API Platform" href="http://www.mashape.com/">Mashape API platform</a>. Mashape allowed me to quickly add a layer on top of our existing API, that only prints posters. Instead of using Document IDs like the main system, it just takes settings like poster size, paper stock, lamination and mounting.<p></p>
The new Mimeo Poster Printing API has 5 methods:<p></p>
<img src="http://kinlane-productions.s3.amazonaws.com/mimeo/posters-sample.png" alt="" align="right" />
<ul class="mainlist">
	<li>getOrderQuote</li>
	<li>getOrderStatus</li>
	<li>getProof</li>
	<li>getQuote</li>
	<li>getShippingOptions</li>
	<li>placeOrder</li>
	<li>prepareProof</li>
</ul>
It provides everything you need to offer poster printing from your application, without the extra steps of setting up a Mimeo.com account, building documents, and using the Mimeo Connect Cloud Print API. But if you want to use the API with your Mimeo Account you can.<p></p>
The Mashape platform provides very simple documention, an API tester, and code libraries in Java, Ruby, Python, PHP and Obj-C.<p></p>
The new<a title="Mimeo Poster Printing API" href="http://www.mashape.com/apis/Poster+Printing+API">Mimeo Poster Printing API</a>is only in alpha. It will place live orders, get live quotes, proofs, etc. But it curently uses a development URL and their is no SSL encrypting transmissions. So use at your own risk.<p></p>
I'm currently finishing the Mimeo account override and adding options for using against the Mimeo sandbox. I'm looking for some alpha testers who want to use it in their application, let me know if you do not have a Mashape account I can probably get you an invite.