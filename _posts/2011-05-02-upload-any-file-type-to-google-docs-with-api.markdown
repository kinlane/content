---
layout: post
title: 'Upload Any File Type to Google Docs with API'
---
<img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/google/google-docs-upload-any-file-type.png" alt="" width="300" align="right" />Over the next few days google will be rolling out the <a title="ability to upload any file type to Google Documents List API" href="http://googleappsdeveloper.blogspot.com/2011/05/upload-all-file-types-to-any-google.html">ability to upload any file type to Google Documents List API</a> for all accounts.<p></p>
Previously only Google Apps for Business users could upload any file type.<p></p>
This opens up Google Docs as a true cloud storage solution. You can store any file type through web interface or via the API. This means any application can use Google Docs as the primary file store.<p></p>
To enable uploads for all file types, developers must use the resumable upload feature of the API, and also pass in the ?convert=false URL parameter.<p></p>
Google has also added checksums to all file that are not converted to a native Google Docs format. This means that if you upload a file type can't be converted, or if you choose not to convert a file to a native format, a checksum is now available to help guarantee the integrity of the file between storage and retrieval<p></p>
With the ability to pay for unlimited storage, ability to upload any file types, and the Google Docs Listing API, Google is now definitely a major player in the cloud storage game.