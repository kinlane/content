---
layout: post
title: 'api-config'
---
<p><a href="http://api-config.apievangelist.com"><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/bw-icons/bw-gear.png" alt="" width="250" align="right" /></a></p>
<p><a href="http://api-config.apievangelist.com/">api-config</a> is my centralized, machine readable JSON format for storing my API configurations in. Each micro service that I deploy has one Github repo that is its central definition, and in the private, master repo, I am storing my api-config.json file.</p>
<p>I rely upon the Github API, and oAuth to read, and write to this config file, allowing each micro service that I deploy to access, and cache the configuration locally, with supporting API endpoints to update when I need.</p>
<p>api-config.json will always be located at a private location, it is up to each micro service to have the path available in APIs.son, or just keep as a known location within the master branch of the repo. Both approaches will use Github security to secure the location.</p>
<p>Since my micro services all live within a single Github organization, I am able to have a central management interface, to globally manage app configurations, to help keep my house in order--we will see how it goes.</p>
<p><a href="http://api-config.apievangelist.com/">api-config</a> is different than api-keys, because it will have a different management process, and will probably remain pretty static, while apis-keys will evolve in alignment with multiple APIs that I use, the authentication schemas I will support, and other realities of API consumption.</p>