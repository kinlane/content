---
layout: post
title: 'Generating Government Services JSON-LD Using Google Doc'
---
<p><a href="http://government.services.publicprivatesector.org/google-doc.html"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/google-drive/bw-google-drive-icon.png" alt="" width="200" align="right" /></a></p>
<p>I wanted to enable people who work in government to generate JSON-LD representations of their services in the easiest way possible. What is the number one way for people in government to manage data? Spreadsheets.</p>
<p>I decided to start with Google Docs, and generate a simple JavaScript tool to take a Google Spreadsheet template that was setup with the required fields for a government services schema.</p>
<p>Next I wrote an import script using Tabletop.js that would grab the contents of the Google Spreadsheet template and using JavaScript to generate the JSON-LD.</p>
<p>You can find this <a href="http://government.services.publicprivatesector.org/google-doc.html">Google Spreadsheet to Government Services JSON-LD tool</a> as a dedicated section on this project site. Everything is written in javaScript and <a href="https://github.com/kinlane/government-services">runs here on Github</a>, so you can fork and employ as your own repository, or you can just generate here and copy, paste and publish where you need.</p>