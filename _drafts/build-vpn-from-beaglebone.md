---
layout: post
title: Building a VPN Server From Beaglebone
tags:
- Blog
- DIY
- Beaglebone
- VPN
---

I started with the idea of building my own NAS. However, after messing around 
for a while, I realized that I don't have the money for that. :(

However, I found out that I can do so many more fun things just with what I have.
I have had this Beaglebone Black since last year, but I didn't really look into
it and plan to do anything interesting with it. After googling some interesting
ideas online, I found out that building a VPN server sounds appealing to me.
There is already an online guide on how to build a VPN from a Raspberry Pi.
I believe if I consult with it and then I can roll out my own VPN from Beaglebone
as well.

**So let's do it!**

## Preparation

Because I already have a Beaglebone Black, there nothing specific I need to
restock before starting this build. Anyone who is interested in this powerful
board in detail can check out [their website](http://beagleboard.org/). I got 
this board as a prize from the CTF in my school, so it didn't cost me *much*.
Like nil.

![Beaglebone Black](/assets/beaglebone.jpg)

## Procedures

### Tune UP Beaglebone

Getting Beaglebone to start working took me a while. After installing all the
drivers provided online, I got it running smoothly only for a short amount of
time. Somehow it got disconnected and I couldn't get it back to work thereafter.
I tried re-install drivers many times, but at the end I figure out the hot plug
doesn't work perfect for my case, and I can only boot up with Beaglebone plugged
and never try to replug it after an unplug.

Anyway, I can move on to update the image as the next step. The [guide](
http://beagleboard.org/getting-started) on their website is rather straightforward 
and I didn't run into any issues.

## Links

Here are some links I found helpful during this build.

[Building VPN with Raspberry Pi from Readwrite](http://readwrite.com/2014/04/10/raspberry-
pi-vpn-tutorial-server-secure-web-browsing#awesm=~oBvYD8BOiTdCQN)
