---
layout: post
title: 'Upload PDF to Mimeo Using REST API'
---
<a href="http://www.mimeo.com/"><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/mimeo-logo.jpg" alt="" width="250" align="right" /></a>I've been <a title="Proofing Documents" href="http://www.kinlane.com/2011/01/proofing-scribd-pdf-using-mimeo-connect/">proofing documents</a> with the Mimeo Connect Cloud Print API.<p></p>
Now I want to start just uploading print files into my Mimeo account.<p></p>
I added support for posting files to the Mimeo REST client.<p></p>
Here is a sample POST to the Mimeo Connect Cloud Print API Storage Service.
<script src="https://gist.github.com/870303.js?file=MCP%20-%20Storage%20Service%20-%20POST"></script><p></p>
Storage Service will create any folder structure you specify when posting file.<p></p>
All files and folders are created in the root /printfileroot folder in the specified My Mimeo account.
