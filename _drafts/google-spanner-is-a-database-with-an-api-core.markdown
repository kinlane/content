---
title: Google Spanner Is A Database With An API Core
date: 2017-05-16 18:29:00 Z
---

I saw the news that Google's Spanner Database is ready for prime time, and wanted to connect it with a note I took at the Google analyst summit a few months back--that gRPC is the heart of the database solution. I'm not intimate with the Spanner architecture, approach, or codebase yet, but the API focus, both gRPC core, and REST APIs for a database platform are interesting.

My first programming job was in 1987 developing COBOL databases. I've watched the database world evolve, contributing to my interest in APIs, and I have to say Google Spanner isn't something I anticipated. Databases have always been where you start deploying an API, but Spanner feels like something new, where the database and the API are one, and the way the database does everything internally and externally is done via APIs (gRPC). 

Now that the database is ready for prime time I will invest some more time in standing up an instance of it and get to work playing with what is possible with the REST APIs. I also want to push forward my grPC education by hacking on this side of the database interface. Spanner feels like a pretty seismic shift in how we do APIs, and how we do them at scale--when you combine this with the elasticity of the cloud, and the simplicity of RESTful interfaces I think there is a lot of possibilities.