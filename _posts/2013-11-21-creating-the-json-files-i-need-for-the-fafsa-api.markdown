---
layout: post
title: 'Creating the JSON Files I need for the FAFSA API'
---
<p>I got a copy of the <a href="http://www.ifap.ed.gov/appprocspecsswd/1314AppProcSysSoftwareDevSpecsAugust2013Update.html">2013-2014 Application Processing System Specifications for Software Developers</a>, to see about generating a data model and API definition for the <a href="/admin/blog/'http:/www.fafsa.ed.gov/fotw1314/pdf/PdfFafsa13-14.pdf&quot;">Free Application for Federal Student Aid (FAFSA) form</a>.</p>
<p>I <a href="http://ed-data.github.io/fafsa-api/2013/11/21/rant-provide-machine-readable-specifications-along-with-pdf-please/">wasn't too happy about having the specifications in PDF format</a>, and after a couple of failed attempts to automatically convert to an excel file I just manually copied the data from tables in the PDF and generated these JSON files:</p>
<ul class="mainlist">
<li><a href="https://github.com/ed-data/fafsa-api/blob/master/fafsa-fields.json">fafsa-fields.json</a></li>
<li><a href="https://github.com/ed-data/fafsa-api/blob/master/conditional_procedures.json">conditional_procedures.json</a></li>
<li><a href="https://github.com/ed-data/fafsa-api/blob/master/rejection-codes.json">rejection-codes.json</a></li>
<li><a href="https://github.com/ed-data/fafsa-api/blob/master/degrees.json">degrees.json</a></li>
<li><a href="https://github.com/ed-data/fafsa-api/blob/master/states.json">states.json</a></li>
</ul>
<p>In my opinion these should be machine readable by default, let alone in a "specification for software developers", but maybe I live in an alternate universe.</p>
<p>Anyhow, I have another page or two of the conditional procedures to put in, but I have the form fields which is what I set out to generate.</p>
<p>Now I can think more deeply about the API architecture and hope to start hammering out an API design and data model.</p>