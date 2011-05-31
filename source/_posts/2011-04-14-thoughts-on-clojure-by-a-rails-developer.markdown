---
layout: post
title: Thoughts on Clojure by a Rails developer
---

You'd really like to learn Clojure for all the benefits that it touts:

- functional without side effects – eliminate bugs, less need to test (muhaha you know that's not real)
- easy to write concurrent code
- first class functions and macros that help create code that write code – hopefully you'd be able to use this to iterate really quickly, even faster than your competition who just uses normal languages like Ruby or Python, just like what Paul Graham says.

However your gripes might be:

- You're not yet familiar with Clojure yet – you know that this can be solved if you can start learning Clojure by working on a side project that you care about
- Off hand the side projects that you can think of now are
  - web applications – because you're hosting it, it doesn't matter what language or framework you're using
  - cross platform apps
- There are already so many useful libraries in Rails that you can use to make things really nicely, and quickly

But Java programmers have this thought too. They have lots of libraries already available that do what they need.

Then you have to ask yourself – why were you unsatisfied with Java? Why did you pick up Ruby?

The answer is probably Rails – the magic of scaffolding that glimmers – made you realize that you can create a databased backed form CRUD app so quickly in Rails.

Soon you had to learn other aspects of the framework that was necessary like authentication – restful_authentication was kinda painful until Clearance came along. Now Devise is pretty neat.

After you followed some Clojure tutorial that sets you up with Compojure on Google App Engine using appengine-magic, you feel kinda lost. There isn't a magic moment yet. You're missing the scaffolding magic. And everything feels very very basic.

Maybe Clojure lets you write JVM apps and you should take advantage of the cross platform portability. Write once and run anywhere. This time without Java and the bugs that come with typical object oriented programming.

Write nice elegant code that allows you to build layer upon layer. Such that you can eventually create a DSL thats actually suits what you need to work on.

But you still feel a little discouraged, a little uncertain. 

Say let's say you want to create a GUI app that runs on all Mac, Windows and Linux. You'd probably have to learn Swing from scratch – Swing feels kinda stressful? Maybe there's a Clojure swing framework for GUI.

Maybe this is the best time to create a framework for cross platform apps that run on all platforms. 

And sell it.