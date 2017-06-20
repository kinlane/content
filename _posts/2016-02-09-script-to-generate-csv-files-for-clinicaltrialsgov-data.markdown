---
layout: post
title: 'Script To Generate CSV Files For ClinicalTrials.gov Data'
---
<p>While the original ClinicalTrials.gov data was broken down into separate machine readable files, it was pipe delimited, which isn't always the breakfast of data champions, so I wanted to make sure it was also available in CSV format to encourage as much reuse as possible, across many different audiences.</p>
<p>With the clinical trials data in a MysQL database, it was very easy to write a script that would output as separate CSV Files</p>
<script src="https://gist.github.com/kinlane/b5522d3bd7bbea92f00a.js"></script>
<p>The script could use some tweaking, and I haven't certified all the data outputed yet, but it has helped me quicklky generate a complete set of clinical trial data in CSV for anyone to download and use all, or part of.</p>