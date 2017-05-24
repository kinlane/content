---
title: How Twitter Hanldes Sorting For Their API
date: 2017-05-24 01:06:00 Z
---

https://dev.twitter.com/ads/basics/sorting

In your API request simply append sort_by=[attribute name]-[asc/desc] where the attribute is a valid attribute that is returned in the JSON of your GET request.

For example, you can use ?name-asc to sort by name alphabetically or ?name-desc to sort in reverse.