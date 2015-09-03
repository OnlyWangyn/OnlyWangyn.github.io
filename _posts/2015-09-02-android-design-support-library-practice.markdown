---
layout: post
title: "Android Design Support Library Practice"
date: 2015-9-02
comments: true
categories: 
---

Hightligh:pls ignore the datetime,I just haven't figure out how to set it correctly.

Recently,I finished practice about Android Design Lib. It's not very difficult,most of widgets from  that lib,I have already applied in my previous projects. Now I just put them together,and commit the demo to the github,hope one day,someone else can get hint from this small project.
Here is link : [DesignLibDemo](https://github.com/OnlyWangyn/DesignLibDemo)

When I did this project,I also read two articles,I think they are good enough for knowing deeply about NestScrolling thing and Animation thing on Android.

I am listing them here:

- [Android 嵌套滑动机制（NestedScrolling）](http://segmentfault.com/a/1190000002873657)
- [Android动画学习笔记-Android Animation](http://www.cnblogs.com/angeldevil/archive/2011/12/02/2271096.html)

As you see,both are Chinese.

Find and resolve issue:  


 It seems CoordinatorLayout and related things only work when setting buildToolsVersion to 22.
 if There is no shadow effect on FloationActionBar even you have already set Elevation Value,pls set app:borderWidth to 0.
