---
layout: post
title: 'Abstract Away the Complexities of Print with an API'
---
<a href="http://www.mimeo.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>When I was being interviewed at Mimeo.com as the API evangelist, one big gap in my resume, that I was concerned about, was no print industry experience. Mimeo is a print company and naturally I should bring something to the table?<p></p>
My boss simply replied, We want someone with the tech, not the print. Someone who can think out of the box. For the first time I feel like I'm putting that lack of skill to use.<p></p>
It took me about 48 hours to get up and running hacking on the <a href="http://developer.mimeo.com/">Mimeo Connect Cloud Print API</a> when I first got hired. I was able to start using the API without any real documentation or help, just hacking.<p></p>
Even though I enjoy this type of hacking, it is about 47.5 hours too long for regular developers. I probably have shortened this time-frame with documentation, FAQ, code samples and how-tos. But there still are some considerable learning curves when it comes to connecting with the Mimeo.com print API.<p></p>
I see developers struggle with two hurdles:
<ul class="mainlist">
	<li><strong>Mimeo User Account(s)</strong> - To use Mimeo start to finish you will need 3 separate accounts. developer area, sandbox API, and live API.</li>
	<li><strong>Document Building</strong> - All final product products are designed as documents. You can assemble one or many print files into a final Mimeo document. The document contains all the final print qualities, such as binding, paper, color, etc.</li>
</ul>
Both these areas provide a lot of flexibility in the Mimeo system, such as a testing environment, and ability to define a wide range of print documents. But they also introduce a substantial learning curve regarding how Mimeo.com operates, before you even can get started using the API.<p></p>
For some developers this is proving to be too much. Currently a developer comes to me and says, I want to print a poster. Simple request. I respond with:<p></p>
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo/posters-sample.png" alt="" align="right" />
<p style="padding-left: 30px;"><em>Start by signing up as a Mimeo.com developer, then setup your sandbox environment. Then login and build the poster you wish to see using Mimeo.com poster builder. When done you right click on the document and grab the product id for your poster. Then you can start making calls against the API to build new posters using that document and any new PDF file.</em>
Too much! I should be saying:
<p style="padding-left: 30px;"><em>Sign up for developer key, make call against this web service with the size of poster and the URL of PDF you wish to print. You can get proof quote, shipping options, and when ready add address and credit card info to actually order a poster.</em>
My first response is already too long, and you actually haven't even reached the actual goal of printing a poster with an API? My second response is short and achieves the desired goal.<p></p>
Last week I set out to fix this. I was losing too many simple requests to print posters. So I set out to add a layer to the Mimeo Connect API (with the resources I have), that abstracts away the complexities of print. I don't want a user to have to think about Mimeo accounts or building documents. I want them to only think about achieving integration with their application.<p></p>
So using <a title="Mashape" href="http://www.mashape.com">Mashape</a>, I'm building simple poster printing API that delivers the desired results. I will be posting more information this week, as it is ready.