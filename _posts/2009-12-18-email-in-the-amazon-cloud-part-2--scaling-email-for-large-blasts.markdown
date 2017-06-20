---
layout: post
title: 'Email in the Amazon Cloud Part 2 - Scaling Email for Large Blasts'
---
I needed to send a large amounts of email. We are talking 500,000 to 1 million emails in each send. These are emails being sent to encourage event attendance or interaction, so they need to go out quickly. The powers that be wanted to have emails go out in 24 hours.<p></p>
In the past we would send emails and then sit and watch servers for 24-72 hours, with constant server restarts and other problems.<p></p>
I came up with a new base configuration that involved using a single blast server for queuing up and sending the personalized emails. This blast server would alternate between several SMTP servers to balance the load and increase the volume at which we could send the emails out.<p></p>
I ran some tests and to achieve the results I wanted it required an SMTP server per 50K emails. I could guarantee emails would go out in about 4-6 hours with remaining trickling out over the next 24 hours.<p></p>
So for a 500k email blast I would fire up an x-large blast instance and 10 large SMTP instances using <a href="http://aws.amazon.com/ec2/">Amazon EC2</a>. I had all the log files for the SMTP servers writing to a common EBS volume that I could maintain the records even after I shut down the instances.<p></p>
I was getting closer to being ready for business. I need to make sure the <a href="http://www.kinlane.com/?p=1100">IP addresses and DNS infrastructure for the email</a> blasts was 100% next.
<p style="text-align: center;"><strong>Email in the Amazon Cloud</strong> - <a href="../?p=1095">Part 1</a> - <a href="../?p=1098">Part 2</a> - <a href="../?p=1100">Part 3</a> - <a href="../?p=1102">Part 4</a> - <a href="../?p=1104">Part 5</a> - <a href="../?p=1106">Part 6 </a>- <a href="../2010/07/email-infrastructure-in-the-amazon-cloud/">Guide  to Email in the Amazon Cloud</a><p></p>
