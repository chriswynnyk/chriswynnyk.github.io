---
layout: post
title: Winter Break 2015
description: Catching up on the latest tech trends
---

Every year, my office takes two full weeks off for the holidays. Which is sweet. It's usually about half a day before I'm back to reading [Hacker News](news.ycombinator.com) and exploring random projects on [Github](www.github.com). 
This year, I set aside some time to learn some new tools.

![SF sign](/img/sf_sign.jpg)

### Terminal multiplexers: tmux vs. screen

What's a terminal multiplexer? It's the Google Chrome of the command line- the utility that lets you tab between multiple black screens with green letters. What's really nifty about these is that when you're connected to a remote server, and get disconnected, a terminal multiplexer lets you reconnect and pick up right where you left off. Kind of like having infinite extra lives in Super Mario Brothers 3.

I had started out using _screen_ years ago, because that's what my mentor was using. I now know of some other folks using _tmux_, which is the relative newcomer of the two. This [StackOverflow Question explains the differences](http://superuser.com/questions/236158/tmux-vs-screen) very well. The main question for me was whether the benefits of using a modern tool outweigh the very high personal cost (re-training my fingers to use _ctrl-b_ vs _ctrl-a_, which is way harder than it should be). 

It's a new year, so why not. I've switched to _tmux_. Here's a [tmux cheatsheet](https://gist.github.com/henrik/1967800) to get you started.

### My development environment

I'm currently doing a rotation on a software development team, which has prompted me to take a second look at tools of the trade. Normally, my typical development work would involve editing files on a client system where _vi_ was the common denominator (and best available editor). It's refreshing to be back working on my own computer where I can install anything I want.

Here were the contenders: 

* [Eclipse Luna IDE](https://eclipse.org/downloads/)
* [IntelliJ IDEA 4](https://www.jetbrains.com/idea/)
* [Atom](https://atom.io/)
* [Sublime Text 3](https://www.sublimetext.com/3)
* [Vi](https://en.wikipedia.org/wiki/Vi) (incumbent)

Yes, yes, I know, this isn't a fair comparison. Some of these are glorified text editors with syntax parser plugins, others are full-blown IDE's, and the last entry is a primitive text editor developed in 1976. That _vi_ could even be a contender is kind of weird.  But that's computer science for you.

#### Eclipse Luna

The defacto IDE for Java development (somewhere in the ~65 - 68% range). Free, reasonably stable, and works with most project setups. My main reason for looking elsewhere were all the little Eclipsisms- the rough edges where I have to modify my workflow or write things manually to accomodate a deficiency in the editor. 

#### IntelliJ IDEA 4

For me, IntelliJ's auto-complete and refactoring were game changers. ZeroTurnaround has a nice [full comparison of Eclipse vs. IntelliJ IDEA 4](http://zeroturnaround.com/rebellabs/getting-started-with-intellij-idea-as-an-eclipse-user/).

#### Atom

This one is an "almost-there". The concept is awesome, with some really nice potential for in-editor rendering and evaluation of web projects. The startup time seems to be noticeably slower as compared to other text editors, and I also seem to get sporadic lag when typing (which is a show-stopper for me). Things seem to have come along since my last experiments with Atom, so I may check back in on this one in another year.

#### Sublime Text 3

Well-polished text editor. Super-fast startup time, nice plugin ecosystem, and just works. This is my primary IDE for anything web.

#### Vi

This will remain my swiss army knife for client-side work and editing configuration files, but otherwise I'm putting _vi_ out to pasture.

### The winners

[IntelliJ IDEA 4](https://www.jetbrains.com/idea/) is now my primary IDE for anything Java, [Sublime Text 3](https://www.sublimetext.com/3) for everything web, and _vi_ for the quick and dirty. So there you have it.

Happy coding!
