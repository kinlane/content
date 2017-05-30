---
title: APIMATIC OpenAPI Extensions
date: 2017-05-27 21:38:00 Z
---

I've added three OpenAPI extensions to the OpenAPI toolbox, adding to the number of extensions I'm tracking on that service providers and tooling developers are using as part of their solutions.  APIMATIC provides SDK code generation services, so their OpenAPI extensions are all about customizing how you deploy code as part of your integration process.

These are the three OpenAPI extensions I am adding:

* x-codegen-settings - These settings are globally applicable to all operations and schema definitions.
* x-operation-settings - These settings can be specified inside an &quot;operation&quot; object.
* x-additional-headers - These headers are in addition to any headers required for authentication or defined as parameters.

If you have ever used APIMATIC you know that you can do a lot more than just "SDK generation", which often has a bad reputation. APIMATIC provides some interesting ways you can augment OpenAPI and dial in SDK, script, and code generation as part of any continuous integration lifecycle.

Yet, another example of how you don't have to live within the constraints of the current OpenAPI spec. Anyone can augment, and extend the current specification to meet your precise needs. Then who know, maybe it will become useful enough, and something that might eventually be added to the core specification. Which is part of the reason I'm aggregating these specifications, and including them in the OpenAPI Toolbox.