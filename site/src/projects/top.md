---
title: Top
emoji: 💻
metaDescription: This is a sample meta description. If one is not present in your page/project's front matter, the default metadata description will be used instead.
date: 2018-01-01T00:00:00.000Z
summary: A Python implementation of the top terminal command
tags:
  - python
  - cross-compatible
  - psutil
  - cron-like
---

### Task

I wanted to write a program that would simulate the kinds of information that the terminal displays after the top command is entered into it in a cross-compatible fashion.

### Solution

In order to implement the task I came up with, I utilized the psutil library. I was able to grab most of the information at the system level as well as most of the process information from the ones that a process has access to see. I was able to do this process for the main 3 operating systems: MacOS, Windows, and Linux/Ubuntu.

##### Link to GitHub Repository

<https://github.com/burgess01/top>
