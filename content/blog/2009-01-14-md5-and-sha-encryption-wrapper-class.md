---
title: C# MD5 and SHA encryption wrapper class
date: 2009-01-14 00:00:00 Z
permalink: "/csharp/md5-and-sha-encryption-wrapper-class/"
tags:
- csharp
- encryption
Published: 2009-01-14 00:00:00 Z
author: Chris S
description: This is a simple utility class for MD5 (128bit) or SHA-2 (256bit,384bit and
  512bit) hash encryption. It outputs the string using 2 byte hex values, e.g. AB12FE.
  It doesn't include SHA-1 but that's trivial to add.
layout: post
dsq_thread_id:
- 1073011737
---

This is a simple utility class for MD5 (128bit) or SHA-2 (256bit,384bit and 512bit) hash encryption.

<!--more-->

It outputs the string using 2 byte hex values, e.g. AB12FE. It doesn't include SHA-1 but that's trivial to add.

`gist:yetanotherchris/4742910`