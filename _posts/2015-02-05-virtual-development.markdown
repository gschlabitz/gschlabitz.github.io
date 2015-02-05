---
layout: post
title:  "Virtual Zen Machine"
date:   2015-02-05 17:25:00
categories: pro tip
---

When I first got my MacBook, I was delighted to find Unix under the hood. Being able to use my regular web development environment was an awesome bonus of the new sleek machine in front of me.

I happily installed all kinds of tomtoolery learning about [ports][ports], [finks][fink], and [homebrews][homebrew], went on a config rampage with system files, setup dev sites using the built-in Apache server, the usual stuff.

After a while, though, I wondered what do these libs leave behind clogging up my silent but kinda medium sized SSD? Do I really want to run three different databases in the background constantly? Wait, is this a stock system lib or did I install that?

Then there was that day where I accidentally `rm -rf`-ed a system folder. Fun! I eventually was able to put it back with the recovery partition that came with my Mac. Thanks Apple!

I knew there had to be a way to make this work without polluting my system everytime I needed to try out some new server tech.

The answer is: __use virtual machines__. You set up a new machine for each specific project environment and can configure the jimmies out of it without stressing about your host OS. If something goes completely sideways, simply delete the virtual machine and start over.

Wich of the many virtualization softwares to use? I recommend [Parallels][parallels]. I mainly use it for Linux environments, but once in a while I need to run a Windows, or even an OS X machine, and it does it with aplomb.

[ports]: https://www.macports.org
[fink]: http://www.finkproject.org
[homebrew]: http://brew.sh
[sublime]: http://www.sublimetext.com
[tower]: http://www.git-tower.com
[parallels]: https://www.parallels.com/
