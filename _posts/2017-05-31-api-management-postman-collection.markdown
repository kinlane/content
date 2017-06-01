---
title: API Management Postman Collection
date: 2017-05-31 19:21:00 Z
---

I have been encouraging API providers to publish and manage their API definitions using Github similar to how you'd manage any code. Companies like Box and NY Times are publishing their OpenAPI definitions to a single repository, allowing partners and API consumers to pull the latest version of the API definition and use throughout the API lifecycle.

I stumbled across another example of managing your API definitions using Github, but this time it is the [management of your Postman Collections in a Github repo from API management provider Apigee](https://github.com/apigee/apigee-management-api-postman) (now Google). The Postman Collection provides a complete description of the Apigee API management surface area, allowing API providers to automate or orchestrate their API operations.

The Github repository providers a complete Postman Collection, along with instructions on how to load, as well as a Run in Postman button allowing any consumer to instantly load the entire surface area of the Apigee API management solution into their Postman Client. I am a big fan of managing your Postman Collections, as well as OpenAPI definitions in this way, managing the definitions for your API similar to how you manage your code, but also making available for forking, checking out, and integrating these machine readable definitions anywhere in the API lifecycle.