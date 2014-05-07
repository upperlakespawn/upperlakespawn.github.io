---
layout: post
title:  "Full bleed headers"
date:   2014-05-06
categories: programming
---


# Auto-margin & max-width

After you do all that you want to go into your layout and nest a container class in your header but put it in its own div inside the header div and it will allow your header color to go all the way to both edges of the screen while still keeping the header text centered with the rest of the page. very useful. >

First thing you want to do is put a auto margin like this -> margin-left:auto; margin-right:auto; those will keep the page centered no mater what. After doing the auto margins you want to put -> max-width:1000px; which will also help keep the page center and will resize your page for what ever size computer or mobile device you are using.

# Full bleed header

if you do not have a div class="container" nested in your header your header color will not go full bleed(from edge to edge) so what you want to do is -> div id="header"  div class="container" <- then close the div after everything that is going to be part of the header.