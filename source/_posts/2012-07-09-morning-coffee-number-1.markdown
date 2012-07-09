---
layout: post
title: "Morning Coffee #1"
date: 2012-07-09 09:07
comments: true
categories: 
- Morning Coffee
- iOS
- Vim
- JavaScript
---
__Morning Coffee #1__

* __[Cupertino:](https://github.com/mattt/cupertino)__ I'm a big fan of the command line (at least when we are talking about development), so when I see a new tool, that eliminates yet another necessity to tolerate some web-based UI, it makes my heart sing. [ Matt Thompson ](http://mattt.me/) (of [Induction](http://inductionapp.com/) and [ AFNetworking ](https://github.com/AFNetworking/AFNetworking/) fame among other things) came up with [Cupertino](https://github.com/mattt/cupertino) - command line tool/gem to automate things we normally do through the Apple's Developer Portal, like managing devices, certificates etc. This is a perfection:
  - `$ ios devices:list`
  - `$ ios devices:add "iPad 1"=abc123`
  - `$ ios devices:add "iPad 2"=def456 "iPad 3"=ghi789 …`
* __[vim-powerline](https://github.com/Lokaltog/vim-powerline)__: I'm a big fan of Vim and I'm definitely going to post some Vim goodies in this blog almost daily, but I'd like to start with my recent discovery - [ vim-powerline ](https://github.com/Lokaltog/vim-powerline). 
![](https://a248.e.akamai.net/camo.github.com/3ea0c5e8e1da9827156bdd3d4af028fc2502f6ea/687474703a2f2f692e696d6775722e636f6d2f78466d4f742e706e67)  
It turns a standard Vim's status line into the prettiest thing ever, but also packed with the functionality. For me, two things are absolutely critical - it changes color when you change the editing mode, which makes it super-easy to figure out if you're in Normal or in Insert mode and it highlights your current pane, which alleviates my biggest pain with multiple panes (no pun intended) - I constantly lose track of what is my currently active pane. This little plugin cures both problems and does it with a style. 
The only caveat is that it requires special patched fonts to display all those fancy characters, so it's slightly less portable, but installation of those fonts takes about a minute and it looks so good, that I don't really care about this extra step. 
By the way, my own command line tools settings (aka 'dotfiles') are available [here](https://github.com/xenocid/dotfiles).
* __[Preparing Yourself for Modern JavaScript Development](http://www.codethinked.com/preparing-yourself-for-modern-javascript-development)__: Pretty good articles explaining how modern, complex JavaScript apps are composed. It's important, because there's a pretty big leap between understanding the basics of JavaScript that will allow you to read (and write) simple code snippets and ability to tackle some modern JS framework like [Ember.js](http://emberjs.com/) or [Backbone](http://backbonejs.org/), let alone write something similar. This article is a good bridge between those two states.
