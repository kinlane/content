---
layout: post
title: 'Optical Character Recognition (OCR) with Google Docs API'
---
Using the <a href="http://code.google.com/apis/documents/" target="_blank">Google Docs List API</a> you can convert high-resolution PDFs or images into editable text using <a class="zem_slink" title="Optical character recognition" rel="wikipedia" href="http://en.wikipedia.org/wiki/Optical_character_recognition">Optical Character Recognition (OCR)</a>.
<a href="http://www.soliddocuments.com/info.htm?id=233&amp;product=SolidPDFTools&amp;subject=CreateSearchableLayer" target="_blank"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo/PDF-OCR.png" alt="" width="250" align="right" /></a>
Google Docs List API can extract the text from the following document formats:
<ul class="mainlist">
	<li>PDF Document (application/pdf)</li>
	<li>JPG Image (image/jpeg)</li>
	<li>PNG Image (image/png)</li>
	<li>GIF Image (image/gif)</li>
</ul>
OCR is an experimental API feature and has a quota in place, limiting the number of calls that can be made.  API quota is higher for Google Apps for Business users.<p></p>
OCR is available through the API by including the ocr=true parameter when uploading a file, then produces a separate Google Docs with extracted text for each uploaded PDF or Image.
