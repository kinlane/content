---
layout: post
title: 'Jekyll: Use Permalink Frontmatter To Simplify File Structure'
---
<p><img style="padding: 15px;" src="https://s3.amazonaws.com/kinlane-productions/ben-balter/ben-balter.png" alt="" width="150" align="right" /></p>
<p>I'm still learning all about running Jekyll on Github Pages for all my projects. My mentor on the subject and Githubber, Ben Balter (<a href="https://twitter.com/BenBalter">@benbalter</a>), gave me some tips today on more efficient use of front end matter with Jekyll.</p>
<p>When I moved from custom PHP sites to using Jekyll, I had many pages that were historically setup using a folder structure, such as&nbsp;<span>/foo/index.php, so when I migrated to run a Github I naturally setup as&nbsp;<span>/foo/index.html.</span></span></p>
<p>Ben pointed out that a better way to do this was using permalink frontmatter,&nbsp;allowing me to store them as /foo.html and use the permalink: /foo/ directive to control their output.</p>
<p>This approach will leave me with a much cleaner, easier to manage file structure. I will be working to migrate all project site structures to use this methodology and add here as a Hacker Storytelling tip.</p>