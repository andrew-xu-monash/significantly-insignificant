---
title: Testing, attention please
author: Andy
date: '2019-11-09'
slug: testing-attention-please
categories: []
tags: []
description: ''
thumbnail: images/tn.png
---

10:32pm

Just bought the domain "significantly-insignificant" for about $11. Currently trying to upload a static version of this blog online. But holy shit is it hard. I've spent literally the whole night fixing bugs and googling my way through how to build the site via Netlify, but goddam this is difficult.

I'm going to go through the "rubber ducky" approach, where I explain my troubleshooting & thought process step by step: 

1. Open the R project directory, and created a public folder via the command "blogdown::hugo_build()".
2. Uploaded all the files within the public folder onto my github.
3. Deployed the site via Netlify through the github repository.

However, the error line "Error running command: Build script returned non-zero exit code: 255" always shows up.

The problem is though, when I google this problem, the only solution suggestions that come up is related to the fact that others did not use the correct versions of Hugo. However, I'm pretty sure that this isn't a problem in my case since I used both version control built within Netlify and an external netlify.toml file to try to bypass it.

Currently don't know a workaround this, will probably consult Mitch next week regarding this problem and see what he thinks.



10/11/2019 11:39am

Ok don't actually need Mitch, just figured it out. Turns out I needed to upload the entre source code folder onto Github. 

I could've saved myself ~4 hours of work if I actually read the instructions properly. Classic.
