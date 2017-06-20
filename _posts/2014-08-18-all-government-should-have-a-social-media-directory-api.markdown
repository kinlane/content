---
layout: post
title: 'All Government Should Have A Social Media Directory API'
---
<p><a href="http://www.cityofchicago.org/city/en/narr/misc/social_media.html"><img style="padding: 10px;" src="https://s3.amazonaws.com/kinlane-productions/city-government/chicago/Chicago_city_seal.png" alt="" width="150" align="right" /></a></p>
<p>I was just looking for a list of Twitter accounts for the City of Chicago, and I came across the <a href="http://www.cityofchicago.org/city/en/narr/misc/social_media.html">standard social media directory page</a>, you will find at most city, county, and state government websites.</p>
<p>After looking at the list, I had a decision to make. I could either manually enter each of the twitter accounts into my CRM, or I could write a script to scrape the page, harvest the cotent and put into my CRM for me--I prefer to write scripts over data entry any day.</p>
<p>Here is the resulting JSON:</p>
<script src="https://gist.github.com/kinlane/1eefd411c707118c5357.js"></script>
<p>It got me thinking that every government entity, whether city, county or state should have a <a href="http://www.usa.gov/About/developer-resources/social-media-registry.shtml">social media directory API like you find for the federal government</a>. We should never have to scrape a list of our government social media accounts.</p>
<p>Once their is an API for each government entity, we can then drive existing websites, and other current locations with the API, as well as use in any new web or mobile apps.</p>