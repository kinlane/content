---
title: How Twitter Handles Sorting For Their API
date: 2017-05-24 01:06:00 Z
---

I was looking into some of the common approaches to how API providers allowing for sorting of data in API responses. I'm not in the business of finding the right answer, I am in the business of finding successful examples from APIs(brands) that people are familiar with--[I thought Twitter's page in their API documentation dedicated to sorting was worth noting](https://dev.twitter.com/ads/basics/sorting).

When you craft your Twitter API request you just append sort_by=[attribute name]-[asc/desc] where the attribute is a valid attribute that is returned in the JSON of your GET request. An example of this is using ?name-asc to sort by name alphabetically or ?name-desc to sort in reverse. Providing a pretty basic approach that API providers can consider when designing sort functionality in their API.

