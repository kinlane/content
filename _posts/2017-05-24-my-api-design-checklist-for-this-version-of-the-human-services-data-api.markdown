---
title: My API Design Checklist For This Version Of The Human Services Data API
date: 2017-05-24 05:01:00 Z
---

I am going through my API design checklist for the Human Services Data API work I'm doing. I'm trying to make sure I'm not forgetting anything before I propose a v1.1 OpenAPI draft, so I pulled together a simple checklist I wanted to share with other stakeholders, and help keep me focused.

First, to support my API design work I got these areas of defining the API in order:

* JSON Schema - I generated a JSON Schema from the [HSDS documentation](https://openreferral.readthedocs.io/en/latest/reference/#objects-and-fields). 
OpenAPI - I crafted an [OpenAPI for the API](https://openreferral.github.io/api-specification/definition/yaml/), generating GET, POST, PUT, and DELETE methods for 100% of the schema, and reflective its use in the API request and response.
Github Repo - I published it all in a Github repository for sharing with stakeholders, and programmatic usage across any tooling and applications being developed.

Then I reviewed the core elements of my API design to make sure I had everything I wanted to cover in this cycle, with the resources we have:

* Domain(s)
* Versioning
* Paths
* Actions
* Verbs
* Parameters
* Headers
* Body
* Pagination
* Data Filtering
* Schema Filtering
* Sorting
* Operation ID
* Requirements
* Status Codes
* Error Responses
* Media Types

After being down in the weeds I wanted to step back and just think about some of the common sense aspects of API design:

* Granularity
* Simplicity
* Readability
* Relationships


