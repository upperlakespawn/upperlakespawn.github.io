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

create a nice hyper link with
   
    <%= link_to 'My Site', 'http://mysite.com' %>



goes and finds image in source/images then posts to page
   
    <%= image_tag 'logo.png' %>



puts five sentences of lorem on your page.

    lorem.sentences 5



puts a place holder image of what ever dimesions you put in.
 
    <%= image_tag lorem.image('100x100') %>

To the action loop in this case six times
    
    <% 6.times do %>
    <% end %>