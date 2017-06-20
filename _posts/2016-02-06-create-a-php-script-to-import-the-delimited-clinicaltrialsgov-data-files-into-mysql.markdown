---
layout: post
title: 'Create a PHP Script To Import The Delimited ClinicalTrials.Gov Data Files Into MySQL'
---
<p>Now that I <a href="https://clinicaltrials.gov/ct2/resources/download">downloaded and unzipped the ClinicalTrials.gov data</a>, I need to import it into a MySQL database for better processing. To assist me, I wrote a simple script for spidering the folder where I downloaded the files, then created a table in the MySQL database I setup, for each file. After each table is created, it imports the delimited data into the database.</p>
<script src="https://gist.github.com/kinlane/b63f9d616cf920a32a16.js"></script>
<p>You are welcome to use the script, its not perfect, but it got the job done! Minimum viable functionality. Maybe I'll polish it and move it forward with other projects, and teach it to use multiple formats--we will see.&nbsp;</p>
<p>I'll get in here and document things soon too.</p>