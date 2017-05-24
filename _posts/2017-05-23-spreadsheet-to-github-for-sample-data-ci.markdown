---
title: Spreadsheet To Github For Sample Data CI
date: 2017-05-23 20:30:00 Z
---

I'm needing data for use in human service API implementations. I need sample organizations, locations, and services to round off implementations, making it easier to understand what is possible with an API, when you are playing with one of my demos.

There are a number of features that require there to be data in the system, and is more convincing when it has intuitive, recognizable entries, not just test names, or possibly latin filler text. I need a variety of samples, in many different categories, with a complete phone, address, and other specific data points. Now, I also need this across many different APIs, and ideally, on demand when I set up a new demo instance of the human services API.

To accomplish this I wanted to keep as simple as I can so that non-developer stakeholders could get involved, so I set up a Google spreadsheet with a tab for each type of test data I needed--in this case, it was organizations and locations. Then I created a Github repository, with a Github Pages front-end. After making the spreadsheet public, I pull each worksheet using JavaScript, and write to the Github repository as YAML, using the Github API.

It is kind of a poor man's way of creating test data, then publishing to Github for use in a variety of continuous integration workflow. I can maintain a rich folder of test data sets for a variety of use cases in spreadsheets, and even invite other folks to help me create and manage the data stored in spreadsheets. Then I can publish to a variety of Github repositories as YAML, and integrated into any workflow, loading test data sets into new APIs, and existing APIs as part of testing, monitoring, or even just to make an API seem convincing.

I have a spreadsheet opened up, and two scripts, one for pulling organizations, and the other for pulling locations--both which publish YAML to the _data folder in the repository. I'll keep playing with ways of publishing test data year, for use across my projects. With each addition, I will try and add the story to this research, to help others understand how it all works. I am hoping that I will eventually develop a pretty robust set of tools for working with test data in APIs, as part of a test data continuous publishing and integration cycle.