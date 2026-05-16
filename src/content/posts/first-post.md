---
title: "Hot Take: Less (Code) Is More"
description: "Bloatware is back, but we must resist!"
pubDate: "May 13 2026"
heroImage: "../../assets/posts/first-post/balance.jpg"
minutes: 5
---

Recently I was successfully rage-baited by a CEO boasting:

_"37K LOC per day across 5 projects...Still speeding up"_

![X Post](../../assets/posts/first-post/1.png "X Post")

[See here](https://x.com/garrytan/status/2038555792052506941)

I understand the evolving landscape of Agentic Engineering allows us to "move" faster than ever before.

But the question STILL remains...

#### "Where to?"

<br>

Even after reading his response to the community backlash [here](https://x.com/garrytan/status/2045404377226285538) and perusing the github of the alleged project, I'm still confused on what the Product or Service or App (or Advice?) is being marketed to me.

This isn't a bash on trendy AI.

<u>Definitely</u> leverage it as a tool to write better code.
Code that **_you_** will be responsible for.

To read, maintain, and build upon.

Carelessly vibe-coding is a recipe for ~~slop~~ disaster.

& unless you yourself can properly read and contextualize 37k lines of code a day, **_and still speed up_**, you would eventually hit a limit on your own understanding of the codebase, just like the AI agents themselves!

### Now nobody knows!

<br>

Regardless, I stand firm in believing that generally:

"Less (Code) is More"

With less code (again, generally):

- Your app is more accessibile to Users (faster load times)
- Testing becomes easier
- Production issues are quicker to diagnose and resolve
- Design and architecture becomes clearer
- Build and deployment times are reduced
- <b>Less resource usage ($$$)</b> (AI, Hosting, Networking)
- Less mental fatigue for developers & agents leading to faster feature delivery

<br>

With all those benefits there has to be a cost right?

Yup.

The cost is in **_keeping_** the code to a minimum, yet understandable and clear.

During my last _"sprint"_ of a hobby project, I was able to deliver new features AND increase performance while ending up with LESS code than I originally started with!

From 20,490 measely lines to 20,068.

About a ~2% code reduction. Not a lot. But...less.

How, you say?

By **_Refactoring_**. Old school style.

Specifically, by leveraging: Design Patterns, DRY Principles, YAGNI, and the like.

The ragebait X post motivated me to create a script to observe the growth of my own App's main codebase:

`git ls-files --directory src/ | grep -E '\.js|\.ts|\.svelte' | xargs wc -l`

All it does is count the lines per file tracked by git and also calculates the sum of them all.

(For now I really only care about \*.js, \*.ts, \*.svelte files)

![Screenshot of LOC Script](../../assets/posts/first-post/2.png "Screenshot of LOC Script")

I run it after each story I complete to see whether I'm up/down from before.

Its not meant to place a hard limit on lines of code, but instead, to say:

With only ~20k lines of code so far, my app is/has:

- An offline music player
- Themeable
- Crossbrowser
- Responsive to multiple devices
- Custom API support for non-local music management
- Caching enabled
- 2d/3d visualizations

<br>

And theres still room for improvement, as always!

Til next time, Ciao...

<br>
<br>

Some Further Reading:

- [Kristijan Kralj X Post on Refactoring By Martin Fowler](https://x.com/kristijan_kralj/status/1992858332059607143)

- Program optimization - [Program optimization](https://en.wikipedia.org/wiki/Program_optimization)
- Extreme minimalism and obfuscation (for funsies) - [International_Obfuscated_C_Code_Contest](https://en.wikipedia.org/wiki/International_Obfuscated_C_Code_Contest)
