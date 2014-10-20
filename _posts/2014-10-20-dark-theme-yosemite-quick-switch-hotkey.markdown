---
layout: post
title: "Dark theme (Yosemite) quick switch hotkey"
date: "Mon Oct 20 22:52:19 +0100 2014"
tags:
- yosemite
- osx
- dark theme
- themes
- hotkey
- apple
---
The new dark theme looks great and at night seems like a good option to use,
but browsing every single day throught settings and more settings to change
this, it's a pain in the ass.

Looks like a guy found a way to switch between the dark theme and the light
theme with a global hotkey... without apps, at all.

Open your Terminal.app or iTerm and type this:

``` bash
sudo defaults write /Library/Preferences/.GlobalPreferences.plist
_HIEnableThemeSwitchHotKey -bool true
```

Log-out and you're done.

Happy toggles.

[Source:
Reddit](http://www.reddit.com/r/apple/comments/2jr6s2/1010_i_found_a_way_to_dynamically_switch_between/)


