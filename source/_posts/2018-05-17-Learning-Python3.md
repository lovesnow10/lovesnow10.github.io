---
title: Learning Python3
date: 2018-05-17 11:30:34
tags:
---

# New features

* Unpacking (Using \*)

`a, b = range(2)` -> a = 0, b = 1 | Already featured in python2.7

`a, b, *rest = range(4)` -> a = 0, b = 1, rest = [2, 3] | New in python3!

`first, *_, last = f.readlines()` -> Get the first line and last line of file.

`def func(a, b, *args)` -> `def func(*args): a, b, *_ = args`

* Keyword only arguments

`def func(a, b, *args, option=True)` -> `func(a, b, option=True)` | What we do in python2.7

`def func(a, b, *, option=True)` -> `func(a, b, option=True)` | In python3

it forced you to pass the arugument with the key name "ie. option". In this way, you can add new arguments without breaking the API.

# What you can't do

* print

_print_ in **Python3** is a function, which means you must using `print("Hello World!")` instead of `print "Hello World!"`.
