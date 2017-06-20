---
layout: post
title: 'Pulling a PDF Using Scribd API and PHP'
---

<div style="padding: 5px;">This call returns an XML response containing relevant file information:</div>
<div style="border: 1px solid #000; width: 540px; padding: 10px; margin: 10px; text-align: left;">&lt;rsp stat="ok"&gt;
&lt;download_link&gt;http://documents.scribd.com.s3.amazonaws.com/docs/2kjfqelznknvkv5.pdf?t=1284562355
&lt;/download_link&gt;
&lt;title&gt;
The Future of Reading and Publishing is Social
&lt;/title&gt;
&lt;page_count&gt;4&lt;/page_count&gt;
&lt;height&gt;792&lt;/height&gt;
&lt;width&gt;612&lt;/width&gt;
&lt;dpi&gt;72&lt;/dpi&gt;
&lt;/rsp&gt;</div>
Now I can pull the PDF file and begin using for my cloud print ordering process. Next I will need to proof the document before I can display for the user.