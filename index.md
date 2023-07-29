---
title: Making an independent website
description: How to make an independent website with GitHub Pages.
author:Justin Kinda
---

[//]: # (Enable responsive viewport)

[//]: # (atom & rss feed)
<link href="https://kbroman.org/simple_sitenil" type="application/atom+xml" rel="alternate" title="Sitewide ATOM Feed">
<link href="https://kbroman.org/simple_sitenil" type="application/rss+xml" rel="alternate" title="Sitewide RSS Feed">

# Making an independent website

This is what to do if you just want a website. (This page is a bit long, but it’s really not that much work.)

## First things

Start by cloning [the repository for the present site](https://github.com/kbroman/simple_site). (Or, alternatively, fork it and then clone your own version.)

```shell
git clone git://github.com/kbroman/simple_site
```
Then change the name of that directory to something meaningful.

```shell
mv simple_site something_meaningful
```

(Of course, replace something_meaningful with something meaningful to you.)

Now change into that directory and remove the .git directory (because you don’t want the history of the my  repository)

```shell
cd something_meaningful
rm -r .git
```
