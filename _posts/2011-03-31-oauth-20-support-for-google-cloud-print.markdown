---
layout: post
title: 'OAuth 2.0 Support for Google Cloud Print'
---
<img src="http://kinlane-productions.s3.amazonaws.com/OAuth2.png" alt="" width="200" align="right" />Up until now Google Cloud Print has only support the <a title="Coogle Client Login" href="http://code.google.com/apis/accounts/docs/AuthForInstalledApps.html">Google Client Login</a>.<p></p>
Google Cloud Print now supports <a title="OAuth 2.0" href="http://wiki.oauth.net/w/page/25236487/OAuth-2">OAuth 2.0</a>.<p></p>
The XMPP print job notification system does not yet recognize the OAuth token, but will shortly.<p></p>
For now users can just use /fetch polling as long as its minimal, and resume using XMPP for print jobs notification when its ready.<p></p>
To make an XMPP connection with OAuth2 developers will need to change &lt;X-Google-Token&gt; to &lt;X-Oauth2&gt; and rename the channel from "cloudprint.google.com/&lt;PRINTER_ID&gt;" to "cloudprint.google.com"