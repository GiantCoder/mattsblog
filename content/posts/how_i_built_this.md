---
template: post
title: How to setup a similar site (should you want to, of course) 🤷🏼‍♂️
slug: setting-up-this-site
socialImage: /media/matt.jpg
draft: false
date: 2021-03-15T22:43:00.169Z
description: How this site was setup
category: Coding
tags:
  - Coding, Gatsby
---
Just in case you were wondering how this site was built - I'm sure you weren't at all bothered to know, but in any case - this was an experiment with Gatsby, which is a very handy tool for quickly generating static websites. I used the Starter Lumen pack for this particular one, but do plan to modify it. I could have built it from scratch, of course, but this was a learning experience for me.

It's pretty simple, if you're comfortable using the Console on a Mac and are patient. You could have a similar site up and running within 30 mins. A couple of caveats, though - sometimes the docs are not exactly accurate, so you need patience when you try a starter pack like I did and find that libraries have been updated and now some of your dependencies don't want to play nicely with each other. It took some educated guesswork and I had to read several posts about similar issues, before I finally managed to get rid of one particular error message. If you want to see a copy of the packages I ended up with, just check the repo ([https://github.com/GiantCoder/mattsblog]). Once that particular hurdle had been leapt, it was simply a case of following very simple instructions to get Netlify to pick it up from my Github account (yes, you do need to know how to use Git, but that's also really straight forward) and then Netlify will just deploy updates automatically (after running some tests).

You can also then edit posts from your laptop, using whatever text editor you prefer (I'm using Visual Studio Code right now) or you can setup Netlify CMS and use a web interface to add or edit posts directly in production. Even if you choose the latter method, Netlify also picks up on those amendments and sorts everything out. What is more, those changes are all synced really easily with your Git repo, so when you go back to your console, it knows you're now out of sync with production and prompts you to update your local repo. Pretty neat. 👍🏻

If you didn't understand of the above, don't worry, you will. I never thought I'd understand Vietnamese, but I've learned a little.
