---
layout: post
title: Creating an Rsync deployed photo gallery
---

[Octopress](github.com/imathis/octopress) is a very nice static blogging framework for 2 great reasons:

#### 1. Jekyll

Neat layouts with HAML/SASS and Markdown for posts

#### 2. Rake script

RSync deploy over SSH to your own web host

I really like the Rake SSH deploy with RSync over SSH so why not make something for photo galleries?

### What it should achieve

Some initial thoughts to start with.

#### Manageable folder structure

* A folder would represent a gallery containing
  * 1.png, 2.png, ... x.png
  * captions.haml with Markdown formatting

#### Generate thumbnails

Using RMagick

#### Generate HTML

Using Rake from HAML and the images.