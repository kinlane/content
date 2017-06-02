---
title: The Strip Github Repo They Use To Manage Their OpenAPI
date: 2017-06-02 17:57:00 Z
---

I'm beating a drum every time I find a company managing their OpenAPI on Github, like we would the other code elements of our API operations. Today's drumbeat comes from my friend Nicolas Grenié ([@picsoung](https://twitter.com/picsoung)), who posted Stripe's Github repository for their OpenAPI in our Slack channel for the super cool API Evangelists in the sector. ;-)

Along with the [New York Times](http://apievangelist.com/2017/03/01/new-york-times-manages-their-openapi-using-github/), [Box](http://apievangelist.com/2017/05/22/box-goes-all-in-on-openapi/), and other API providers, [Stripe has a dedicated Github repo for managing their OpenAPI definition](https://github.com/stripe/openapi). This opens up the Stripe API for easily loading in client tools [like Restlet Client](https://restlet.com/modules/client/), and Postman, as we as generating code samples and SDKs using services like APIMATIC. Most importantly, it allows for developers to easily understand the surface area of the Stripe API, in a way that is machine-readable, and portable.


