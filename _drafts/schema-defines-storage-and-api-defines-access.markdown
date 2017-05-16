---
title: The Human Services Schema Defines The Storage And The API Defines Access
date: 2017-05-16 12:00:00 Z
tags:
- HSDS
- Open Referral
- City Government
- Human Services
- Vendors
---

I'm comparing five separate vendor API implementations with the Human Services API standard I'm working on right now. I'm working to push version 1.0 of the API towards a 1.1 with some incremental, forward-thinking changes. 

During This phase, I'm looking to get as much feedback on the API interface from vendors. The Human Services schema is being moved forward by a separate, but overlapping group, and has already gone through a feedback phase, and officially release 1.1 of the schema--I'm doing the same for the API.

Even though the Human Services schema is present, the purpose of the API definition is to open up discussion about what access to that data looks like, with the OpenAPI for the Human Services API acting as a distributed and repeatable contract for how we access publicly available human services data.

The contract provided by the Human Services API defines how stakeholders can access organizations, locations, services. The Human Services schema defines how this human services data is stored, and with the assistance of the API will be defined in transit for every request made of it, as well as the response that is given. 

If we are going to get thousands of municipalities exchanging data with each other, as well as the growing number of applications and systems they are using to serve the public, we will need a shared definition for how data is stored, as well as accessed. As I prepare responses to vendors involved in the feedback loop, I just wanted to gather my thoughts regarding the separation between the schema efforts and the API efforts.