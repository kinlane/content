---
layout: post
title: 'Amazon EC2 Down for 30 Minutes'
---
We were trying to finish up a major email blast tonight and all of a sudden our main blast server stopped working.<p></p>
Then I immediately got a flood of email alerts saying all of our live servers were down.<p></p>
I submitted a trouble ticket to Amazon EC2. I have Gold Support package lately with all the email issues we have been having.<p></p>
I looked at their <a href="http://status.aws.amazon.com/">AWS Status Page</a> and it reported nothing. Then shortly after I submitted my ticket I see they refreshed the status:
<div><em><strong>Power issues in a single availability zone</strong></em></div>
<div><em><strong>
</strong></em></div>
<div>Just the East region was having issues. Our instances in the West zone were fine. This was at the same time they were providing <a href="http://www.kinlane.com/?p=1053">PTR records for our Amazon EC2 email server IP addresses</a>.</div>
