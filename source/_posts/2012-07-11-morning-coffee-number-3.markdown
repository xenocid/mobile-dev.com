---
layout: post
title: "Morning Coffee #3"
date: 2012-07-11 22:54
comments: true
categories: 
- Morning Coffee
- iOS
- Cocos2D
---
* __Most Important Debugging Trick for XCode__: I was recently helping one of my co-workers to figure out
  some nasty exception in his iOS project and remembered a debugging trick,
  which is probably one of the most important ones iOS developer should know. 
  In many cases, your app will crash with some exception, but stack trace will point to your
  UIApplicationMain and will not contain any information about where this exception
  was actually raised. Here's how to get the proper stack trace.
  - Go to Breakpoints panel
  - Press '+' sign on the bottom of it
  - Select 'Add exception breakpoint' and keep all settings at their defaults
  Now if you run your application again and reproduce the error conditions, when
  exception is raised, instead of being caught only by the top-level exception handler and
  lose all the relevant stack trace information, now it will stop at the breakpoint 
  right at the place where exception was originally raised and pointing to the exact
  source of the problem. Enjoy.
  {% img  /images/xcode-exception-breakpoint-1.png Add Exception Breakpoint Dialog %}
* __[List of Useful Cocos2D Tools](http://abitofcode.com/2012/07/cocos2d-useful-tools/)__:
  Nice article mentioning bunch of tools that developers can use in their
  [Cocos2D-based](http://www.cocos2d-iphone.org/) projects. Some of them are quite obvious 
  and not really Cocos2D-related, like Photoshop or Audacity, but it mentions all that are really
  useful and important like [SpriteEditor](http://click.linksynergy.com/fs-bin/stat?id=Vg6WGCcESLE&offerid=146261&type=3&subid=0&tmpid=1826&RD_PARM1=http%253A%252F%252Fitunes.apple.com%252Fus%252Fapp%252Fspritehelper%252Fid416068717%253Fmt%253D12%2526uo%253D4%2526partnerId%253D30), 
  [LevelHelper](http://click.linksynergy.com/fs-bin/stat?id=Vg6WGCcESLE&offerid=146261&type=3&subid=0&tmpid=1826&RD_PARM1=http%253A%252F%252Fitunes.apple.com%252Fus%252Fapp%252Flevelhelper%252Fid421740820%253Fmt%253D12%2526uo%253D4%2526partnerId%253D30),
  [TexturePacker](http://www.codeandweb.com/texturepacker), [Tiled](http://www.mapeditor.org/) etc.
