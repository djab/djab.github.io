---
layout: post
title:  "Brace matching in Terminal"
date:   2013-05-17 15:03:14
categories: coding
---

You can learn a lot from watching how others work. [Peepcode] (http://wwww.peepcode.com), a purveyor of high quality screencast tutorials for web developers, has a special section of "Play by Play" screencasts in which they watch well-known developers tackle a programming task.

Recently, I watched their [screencast] (https://peepcode.com/products/play-by-play-tenderlove-ruby-on-rails) of Aaron Patterson (@tenderlove), who is a contributor to both Ruby and Ruby on Rails.

Within the first few minutes I learned about a great feature that works in both Terminal and iTerm: double clicking on any brace, parenthesis, or bracket will highlight all text in between the matching element.

To give an example, below I have used `curl` to grab some data from the GitHub API:

<img alt='Brace highlighting' src='/assets/images/2013-05-13.png' />

As you can see, it becomes much easier to grok the structure of the responding JSON once we highlight the first enclosed object by double clicking the first opening brace.