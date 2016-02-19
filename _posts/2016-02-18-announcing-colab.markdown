---
layout: post
title:  "Announcing CoLab"
date:   2016-02-18 21:05:03 -0500
categories: general development
---
As some of you might know, I recently got accepted for a research position at the [MIT's CCI][cci] where I'm primarily working on the [Climate CoLab][colab] project.

The current Climate CoLab's codebase is completely written in Java. Generally, I consider Java a fairly decent language with lots of nice features. But from what I can tell based on my past experience, Java projects tend to be overly complicated and unnecessarily bloated. Unfortunately, this is exactly what I think is the case for the project I'm currently working on. Also, the entire platform is rather complex to set up properly.

How can we address all of these issues as quickly as possible? Say hello to CoLab!

CoLab is meant to be a generic, open source collaboration platform completely written in Ruby and inspired by the current Climate CoLab system.

Why Ruby? Because you can get what you want really fast. It's not a secret that lots of startups are relying on Ruby to build their backends and services exactly for this particular reason. While Ruby was often cited as being slow in terms of code execution (well, rather interpretation) this has greatly improved with the most recent releases. And if those small time differences really matter to you, you got to think about serious scaling anyways. If time permits, I'll write a dedicated article about my language decision.

Framework-wise I'll make use of [Sinatra][sinatra] for the API and [Ruby on Rails][rails] for the web client. Both applications will run on [Heroku][heroku] dynos. I'll definitely follow up on the details about the top level architecture in a dedicated post.

Eventually, there'll also be an iOS client, but as for now most of the work will flow into the development of the API and the web client.

As for now, development has just started and the first couple of commits are already live on GitHub ([API][api], [WWW][www], [iOS][ios]). Since I'll only have time to work on this project during my free time, don't expect this project to progress at a rapid pace, but I'm definitely motivated to take this project to a good state. Looking forward to the next months!

[cci]: http://cci.mit.edu
[colab]: http://climatecolab.org
[heroku]: https://www.heroku.com/home
[sinatra]: http://www.sinatrarb.com
[rails]: http://rubyonrails.org
[api]: https://github.com/steverab/colab-api
[www]: https://github.com/steverab/colab-www
[ios]: https://github.com/steverab/colab-ios
