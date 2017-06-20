---
layout: post
title: 'The Green Button API'
---
<p><a href="http://energyos.github.io/OpenESPI-GreenButton-API-Documentation/API/"><img style="padding: 10px;" src="https://s3.amazonaws.com/kinlane-productions/federal-government/green-button/green-button-api-docs.png" alt="" width="250" align="right" /></a></p>
<p>Unlike the work I did around the <a href="http://ed-data.github.io/fafsa-api/">FAFSA API</a>, there is <a href="http://energyos.github.io/OpenESPI-GreenButton-API-Documentation/API/">already a Green Button API</a> setup. The current implementation is just a sandbox version to show what is possible, but the work has been done.&nbsp;</p>
<p>Even better the Green Button API has an API definition in Swagger, which means there is a machine readable API spec for each of the 13 API endpoints. This allowed them to easily create the interactive docs, and means that I can easily generate server side and client side code to work with the current API design.</p>
<p>The Green Button API sandbox references an oAuth implementation, and I know from earlier conversationt that their is an oAuth layer to go with all of this. I think that is where I'll head next to see what work has been done.</p>