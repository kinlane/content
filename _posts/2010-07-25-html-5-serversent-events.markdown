---
layout: post
title: 'HTML 5 Server-Sent Events'
---
<img class="alignnone" style="padding: 15px;" title="HTML5" src="http://kinlane-productions.s3.amazonaws.com/html5.jpg" alt="" width="200" align="right" />As I continue my deep dive into the functional side of HTML5 I am learning about Server-Sent Events. Server-Sent Events enable servers to push data to a web page loaded in the browser.  Think of it as reverse AJAX.<p></p>
Using the EventSource interface you can register and event listener client side.<p></p>
Then server side you send messages using a text/event-stream MIME type.<p></p>
Seems like a much more efficient way of handle server side communications. Changes the way you think UI interactions and where events can be initiated.