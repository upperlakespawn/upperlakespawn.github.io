---
layout: post
title:  "Introduction to Middleman"
date:   2014-05-05
categories: instructions
---

# What is Middleman you ask
Middleman is a static site generatot built with ruby, that can do the same things Jekyll but with the simplicity of ruby.

## Install Middleman
Middleman is a gem so you simply run...

    gem install middleman

## Create a site
The following command will build out everything for your new Middleman site.

    middleman init my-project

## Run the site
Running the following command will start your web server

    middleman

## See it in browser
You can right click and open the link right in your terminal. It should look like this.

    http://0.0.0.0:4567

# Middleman tricks

link_to [will allow you to link two different pages together and add a link.]

image_tag [will allow you to take the location of an image and post the image to your page.]

lorem.sentences 5 [will put five sentences of lorem on your page.]

lorem.image('100x100') [will put a place holder image of what ever dimesions you put in. in this case 100 by 100]