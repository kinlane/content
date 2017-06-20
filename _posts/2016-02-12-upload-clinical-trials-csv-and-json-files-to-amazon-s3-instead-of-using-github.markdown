---
layout: post
title: 'Upload Clinical Trials CSV and JSON Files To Amazon S3 Instead Of Using Github'
---
<p><img style="padding: 15px;" src="http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/blog/amazon-s3.png" alt="" width="250" align="right" /></p>
<p>Originally I wanted to put the data I exported as CSV and JSON files from the clinical trials database on Github, but it is well over 3GB of data, with the limit per repository on Github around 1GB. I really do not want to spread it out across many different repositories, so I went ahead and put it up on Amazon S3.</p>
<p>Amazon S3 is where I store my heavier objects like images, videos, and larger jSON, CSV, and other data files. I can easily link up the data via the <a href="http://adopta-agency.github.io/clinical-trials/">ClinicalTrials.gov Adopta project</a>, in the central _config.yml, and users can easily choose to download any of the over 40 files, and either CSV or JSON--take your pick.</p>
<p>I won't be able to accept pull requests on the clinical trials data files, but will have to find other ways of keeping them up to date. Ideally we do everything via the APIs, and just dump the CSV and JSOn files to Amazon S3 regularly.</p>