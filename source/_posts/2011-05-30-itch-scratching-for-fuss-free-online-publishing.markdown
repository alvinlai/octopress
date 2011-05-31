---
layout: post
title: Itch scratching for fuss-free online publishing
---

Recently, I've had to do quite a bit of online publishing. After going at it for a while, I realized that a good part of the workflow is repetitive and can be automated, so I rolled up my sleeves and scratched the itch.

Introducing 2 generators designed to speed up and simplify the usually tedious process of creating and publishing web content.

## Screendocs – publish step-by-step screenshots easily

A mac application, designed by yours truly, for capturing step-by-step screenshots, generate HTML and publishing it online in one step.

In other words, a really nice way to upgrade that wall of text.

Get [Screendocs Pro for projects and teams](http://screendocs.com) or the [standalone Dropbox version](http://screendocs.com/dropbox).

## Octopress – static blogging framework that's fun for developers

A [Jekyll](https://github.com/mojombo/jekyll) based static blogging framework with nice fsevent-based [Guard](https://github.com/guard/guard) auto generation. 

This is what I'm using to design this website in nice [HAML](http://haml-lang.com) and [SASS](http://sass-lang.com/) and write posts in  [Markdown](http://http://daringfireball.net/projects/markdown/).

The included Rake file allows you to:

- Preview the site via:

    rake preview
    
- Deploy the generated static HTML site Rsync over SSH via:

    rake deploy

This makes deploying to my VPS fuss-free.

Check out my [Octopress edge fork](https://github.com/alvinlai/octopress/tree/edge), which fixes a Google Analytics include bug.

### Why use the Octopress edge fork?

Because it includes the magical Rake tasks mentioned above and works with Ruby 1.9.