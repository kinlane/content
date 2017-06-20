---
layout: post
title: 'Running Your Event in the Cloud - Email'
---
Email is still the number one tool for managing events and communicating  with attendees, speakers, and exhibitors. Social network is definitely  the future of the event communication, but until then email rules.<p></p>
Sending  out call for papers, speaker, exhibitor, attendee invitations and other  emails around a conference can require a well oiled email  infrastructure to make sure emails get into the inbox.<img title="Event Email in the Clouds" src="http://kinlane-productions.s3.amazonaws.com/events-in-the-clouds/email_icon.jpg" alt="" width="250" align="right" /><p></p>
I see  events send anywhere from a few hundred to several million emails over  the life span of an event. Sending emails in the cloud can work well  whether your sending a small amount using Google Apps or millions using  Amazon Web Services.
<ul class="mainlist">
	<li><a href="http://www.google.com/a/">Google Apps</a> is a quick way for events to  setup email at their domain and not worry about email delivery, receipt  and SPAM. It has a 500 daily limit on how much you can send, but works  well for smaller events.</li>
	<li><a href="http://aws.amazon.com/">Amazon Web Services</a> provides even more  industrial strength when it comes to larger events and conferences</li>
</ul>
Amazon  provides the necessary computing power to get emails out the door  efficiently. Now that Amazon allows for reverse DNS on reserved IP  addresses it makes Amazon a viable solution for permanent and temporary  email infrastructure.<p></p>
I often scale primary email infrastructure  from 1 POP / SMTP server to 3 during an event to support ongoing daily  emails. I also will scale up to 10 SMTP servers for 24 hour periods to  support large scale email blasts.<p></p>
<a href="http://aws.amazon.com/ec2/">Amazon EC2</a> is the computing  power, and <a href="http://aws.amazon.com/s3/">Amazon S3</a> is great storage for emails, logs, and more. With a  proper plan strategy, email in the clouds is possible.