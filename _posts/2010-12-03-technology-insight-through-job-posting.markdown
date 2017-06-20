---
layout: post
title: 'Technology Insight Through Job Posting'
---
<img src="http://t0.gstatic.com/images?q=tbn:ANd9GcRrUyAOwIvtJMOZon86UKTOo5WcfYaJ719Sr4_d82j82Uujhsdg" alt="" align="right" />A <a href="../2010/12/ideation-and-project-evolution/" target="_blank">project I'm moving off the back-burner and into the public domain</a> is a project I called Tech Job Analysis.<p></p>
I have been pulling all the job postings in the three technical categories from <a href="http://www.craigslist.com" target="_blank">Craigslist</a> for all the North American and European job markets.<p></p>
I started pulling these RSS feeds and monitoring for the next dream job...which I got. Then I quickly started seeing other value in this data.<p></p>
You can tell a lot about a company by their job postings that you won't see anywhere else. You can see what software, hardware and systems they use. You can see what type of development process they use. There is a a gold-mine of data here.<p></p>
So I started parsing the posts using a master list of technology keywords and key phrases. Example: Hadoop or Cassandra.<p></p>
Then I started storing the city and date, each time these key words would show up. So you could query for the word hadoop and provide a date range....and it would return the City (Count) for the number of job postings that contained the word hadoop.<p></p>
My goal was to provide a real-time tecnology, tool, company API that you could throw a term + date range at and get back a pretty quality data set showing that technologies penetration. Think about merging with <a href="http://www.openheatmap.com/" target="_blank">OpenHeatMaps</a> or other visualizations. Time elapsed? You could see how much hadoop has grown, or how much cassandra has until Facebook and Twitter both abandoned?<p></p>
This is another project I just couldn't keep the EC2 aand RDS accounts up and running if these projects never made it off the back burner. If you are interested, let me know.