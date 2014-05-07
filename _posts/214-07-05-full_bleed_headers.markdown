---
layout: post
title:  "Fit your website to any device"
date:   2014-05-06
categories: programming
---


I am going to show you some code that will optimize your web pages to any size computer or mobile device you are using.

# Auto-margin & max-width

First thing you want to do is put a auto margin like this

    margin-left:auto; margin-right:auto; 

Those will keep the page centered no mater what. Then constrain the width of the page and support collapsing the screen to smaller sizes.

        max-width:1000px;
 

I usually put all this code into a single class called container so i can easily apply it where ever i want it

    .container {
      max-width:1000px;
      margin-left:auto;
      margin-right:auto;
      padding:15px;
    }

# Full bleed background-color

The issue with the above code is that it will auto margin your background colors to deal with this apply your background color to the header then nest a container class in your header.

    	<div id="header">
            <div class="container">
                my site
            </div>
        </div> 

With this approach your header will look alot like mine.