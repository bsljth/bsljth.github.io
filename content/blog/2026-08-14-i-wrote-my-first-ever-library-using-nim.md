---
title: I Wrote My First Ever Library; Using Nim
description: A brief note about my first library.
date: 2023-08-03
draft: false
tags:
  - computing
  - nim
---
I wrote my first ever library using the Nim programming language. You can check it out at its GitHub repo. It's called `<a href="https://github.com/bsljth/printo">printo</a>` (pronounced "print-o"). 

It's a small library. I was initially worried whether it is worth making and making it public. Then, I read the story of `left-pad`[](https://www.davidhaney.io/npm-left-pad-have-we-forgotten-how-to-program/">]([https://www.davidhaney.io/npm-left-pad-have-we-forgotten-how-to-program/)`left-pad`[) and the controversy around it]([https://www.davidhaney.io/npm-left-pad-have-we-forgotten-how-to-program/).

FYI, left-pad was an NPM library that was being used by thousand other projects for adding some padding to a string (yeah, it's true). The controversy around the library was that the author decided to pull the plug on one not-so-fine day which led to the thousand projects using it to break (at least some might have). This was big news.

Anyway, the total lines of code in left-pad was 47 (excluding the types file, package.json etc.). However, 47 lines of code were being used by thousands (actually, about 15 lines are just comments). If this cannot motivate someone to write a library, nothing will.

So, I made `printo`. Enjoy!