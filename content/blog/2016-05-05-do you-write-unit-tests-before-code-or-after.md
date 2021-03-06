---
title: Do you write unit tests before code, or after?
date: 2016-05-05 00:00:00 Z
tags:
- csharp
- testing
- unit-tests
Published: 2016-05-05 00:00:00 Z
author: Chris S
layout: post
shortpost: true
---

One of the biggest omissions in the TDD literature is the concept of code first vs test first. The discussion doesn't seem to surface very often, possibly because it's a more advanced topic.

Both are valid ways of doing TDD, and after many years of doing both I think I've finally settled on a few good ways to decide which method to employ:

#### Test first:

* You're writing business or safety critical code
* You are experimenting with an API etc. that you don't know how to use.
* You are pairing with someone
* Like most of us, you find writing tests later very monotonous work
* You're doing a presentation on TDD


#### Code first

* You're writing a proof if concept, or small home project
* You haven't fleshed out the API you're writing yet, or unsure of it's design
* You're writing code that is so basic, such as de-serialization of a config file, or breaks the system in such an obvious way, tests can be added later
* You're on your own and demotivated


With the code first approach I'm not advocating lowering your test coverage - you would still have the tests in there before you 'ship'.
