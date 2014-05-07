---
layout: post
title:  "Full bleed headers"
date:   2014-05-06
categories: programming
---

describe auto margin and max width and how it deals with diff sized screens.

then how to use a nested container class for full bleed background colors

# Getting a Full bleed header

so first you want to put a auto margin which is what keeps the page centered you also want to put a max width of 1000px which is part of what makes the site mobile compatible and useable if you shrink your browser.

After you do all that you want to go into your layout and nest a container class in your header but put it in its own div inside the header div and it will allow your header color to go all the way to both edges of the screen while still keeping the header text centered with the rest of the page. very useful.