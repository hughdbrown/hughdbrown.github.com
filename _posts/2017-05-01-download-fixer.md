---
layout: post
title: "Download fixer"
description: "New project to replace repeated files with unix soft links"
category:
tags: [data science]
---
{% include JB/setup %}

I've been doing a lot of online courses recently. I've started to notice that there are frequently multiple copies of the same PDF or other asset in multiple directories. I decided to write some code to fix this.

Check out [my github repo](https://github.com/hughdbrown/download_fixer) for python code (installable as a local script) that creates unix soft links to the single copy and deletes the other copies.

