---
title: Spreadsheet To Github For Sample Data CI
date: 2017-05-23 20:30:00 Z
---

I'm needing data for use in human service API implementations. I need sample organizations, locations, and services to round off implementations, making it easier to understand what is possible with an API, when you are playing with one of my demos.

There are a number of features that require there to be data in the system, and is more convincing when it has intuitive, recognizable entries, not just test names, or possibly latin filler text. I need a variety of samples, in many different categories, with a complete phone, address, and other specific data points. Now, I also need this across many different APIs, and ideally, on demand when I set up a new demo instance of the human services API.

To accomplish this I wanted to keep as simple as I can so that non-developer stakeholders could get involved, so I set up a Google spreadsheet with a tab for each type of test data I needed--in this case it was organizations and locations. Then I created a Github repository, with a Github Pages front-end. After making the spreadsheet public, I pull each worksheet using JavaScript, and write to the Github repository as YAML, using the Github API.

