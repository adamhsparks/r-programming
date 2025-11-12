---
title: Instructor Notes
---

This lesson is written as an introduction to R, but its real purpose is to introduce the single most important idea in programming: how to solve problems by building functions, each of which can fit in a programmer's working memory.
In order to teach that, we must teach people a little about the mechanics of manipulating data with lists and file I/O so that their functions can do things they actually care about.
Our teaching order tries to show practical uses of every idea as soon as it is introduced; instructors should resist the temptation to explain the "other 90%" of the language as well.

The secondary goal of this lesson is to give them a usable mental model of how programs run (what computer science educators call a [notional machine](../learners/reference.md#notional-machine) so that they can debug things when they go wrong.

## Teaching Notes

- Watching the instructor grow programs step by step is as helpful to learners as anything to do with R.
  Resist the urge to clean up your R script as you go (which is what you'd probably do in real life).
  Instead, keep intermediate steps in your script.
  Once you've reached the final version you can say, "Now why don't we just break things into small functions right from the start?"
