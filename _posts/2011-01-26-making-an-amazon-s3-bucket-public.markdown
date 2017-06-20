---
layout: post
title: 'Making an Amazon S3 Bucket Public'
---
<table cellspacing="5" cellpadding="5">
<tbody>
<tr>
<td align="center" valign="middle"><img src="http://a0.twimg.com/profile_images/1176550371/5163129933_353fc10a38_m_normal.jpg" alt="Audrey Watters" width="32" height="32" /></td>
<td align="left"><a title="Audrey Watters" href="http://twitter.com/#!/audreywatters">@audreywatters</a> -I don't know how to manage my bucket policies cc @<a rel="nofollow" href="http://twitter.com/kinlane">kinlane</a></td>
</tr>
</tbody>
</table>
<table cellspacing="5" cellpadding="5">
<tbody>
<tr>
<td align="center" valign="middle"><img src="http://a0.twimg.com/profile_images/1100759006/kinlane_normal.jpg" alt="Kin Lane" width="32" height="32" /></td>
<td align="left"><a title="Kin Lane" href="http://twitter.com/#!/kinlane">@kinlane</a> -@audreywatters go to aws console -&gt; find folder -&gt; edit properties -&gt; permissions -&gt; edit bucket policy. I will email policy to you.</td>
</tr>
</tbody>
</table>
Paste this bucket policy with [bucket name] changed to your bucket name.
<blockquote><code> {
"Version": "2008-10-17",
"Id": "57eafc04-1a5c-479b-8106-01828c991cd3",
"Statement": [
{
"Sid": "AddPerm",
"Effect": "Allow",
"Principal": {
"AWS": "*"
},
"Action": "s3:GetObject*",
"Resource": "arn:aws:s3:::[bucket name]/*"
}
]
}
</code></blockquote>