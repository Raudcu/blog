---
title: "Installing Python + Jupyter with Conda"
description: "Setting up Python the right way"
layout: post
toc: true
comments: true
image: images/python-jupyter-conda/header_image.png
hide: false
search_exclude: true
categories: [python, jupyter, conda]
---
![header_img](https://raw.githubusercontent.com/Raudcu/blog/master/images/python-jupyter-conda/header_image.png)

## Introduction

The idea of this post is to try to .... the best way to set up Python in your computer.

This is one of the things that at first glance one assumes is obvious and straightforward, but it's not, at least at the beginning.

Let me put it this way: you have just found about Python and you want to start right away hands-on and start writing some code. What do you do? You most likely are tempted to go to [Python's official](https://www.python.org/) web site, download the appropriate installer for your machine, install it and start coding...that's it, what about all the fuss? Well, the truth is that this won't do.

Let me....  is very straightforward once you know how to do it. But at the beginning it can be pretty overwhelming: which version should I installed? Do I even need to install it or it is already install with my OS? What is `pip`? How do I install python packages? What is all... with environments? Do I need them? How I create them?... don't panic. Again: it's not as hard as it seems to have a very good and clean set up. I'll try to walk you through this jungle. 

This is one of those things that I would very much liked to know when I started. But, sadly, without intend it, I took the dark path and ended as the famous *xkcd* comic ...

Ok, let's start...

![xkcd](https://imgs.xkcd.com/comics/python_environment.png "True")


## Start coding fast

![replit](https://raw.githubusercontent.com/Raudcu/blog/master/images/python-jupyter-conda/replit.png)

Allow me just one last digression. If what you want is to start coding right now. The best option is to use an online tool like [repl.it](https://repl.it/). It's a really a fantastic site that allows you to code in a wide variety of languages, with dark mode, autocompletion and linting, among many other features, and execute the code right there. If your intention is to start as fast as possible, definitely give it a try. If not, let's .....


## Why not going directly with the installer?

The short answer in the long term it will end messing up


## Conda

So the first step is to set up *Conda*. Conda is "an open-source, cross-platform, language-agnostic package manager and environment management system"