---
layout: post
title: 'I Predict We Will Be Using HTTP/1.1 451 Unavailable For Legal Reasons A Lot More In Future'
---
<table width="40%" align="right">
<tbody>
<tr>
<td align="center"><a href="https://sites.google.com/a/depauw.edu/fahrenheit-451-1966-film/themes-of-fahrenheit-451"><img src="http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/fahrenheit-451.jpg" alt="" width="100%" /></a></td>
</tr>
<tr>
<td align="center"><a href="https://sites.google.com/a/depauw.edu/fahrenheit-451-1966-film/themes-of-fahrenheit-451">photo credit</a></td>
</tr>
</tbody>
</table>
<p>I'm playing catch up with some of my news and information curation, something that always builds up when I travel. As part of my work I came across the <a href="http://tools.ietf.org/html/rfc7725">RFC 7725, HTTP/1.1 451 Unavailable For Legal Reasons</a>, providing an HTTP status code for use when access to a resource is denied as a consequence of legal  demands.</p>
<p>The RFC states that, "responses using this status code SHOULD include an explanation, in the response body, of the details of the legal demand: the party making it, the applicable legislation or regulation, and what classes of person and resource it applies to"--something I'm wondering if even will be possible in some situations.</p>
<p>Anyways, I wanted to make sure this HTTP status code was filed as part of my overall API Evangelist consciousness. I have the feeling that we will be using&nbsp;HTTP/1.1 451 Unavailable For Legal Reasons a lot more in the future, and want a reference point to link to. Hopefully someone out there will be tracking the number of 451 status codes that emerge, so we can graph over time how many online resources go 451--I do not have the resources to do it.</p>
<p>Seems like it will be a pretty telling metric of the health of this online experiment, we are calling the web.</p>