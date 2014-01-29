---
layout: post
category : notes
tags : [Notes, Computer, Troubleshooting]
---
{% include JB/setup %}

## Monitor Fiasco January 2014

On my work desktop, I'm running [Ubuntu 13.10 (Saucy Salanader)](http://releases.ubuntu.com/saucy/) and I have (or <i>had</i>, before the <i>foobar</i>) [NVIDIA proprietary graphics drivers](http://www.nvidia.com/object/unix.html) installed.

Just in case something like this happens again, these links helped me get where I was going to solve the issue:

[Ubuntu Community Troubleshooting](https://help.ubuntu.com/community/Troubleshooting)

[How do I reset my display settings from the command line?](http://askubuntu.com/questions/223486/how-do-i-reset-my-display-settings-from-the-command-line)

[Dual monitor problem: larger screen is stuck at lower than maximum resolution](http://ubuntuforums.org/showthread.php?t=2074912)

code: [Fullscreen secondary monitor nvidia](http://pastebin.com/mcweUUZm)

[Can't see display at all!](https://answers.launchpad.net/ubuntu/+source/xserver-xorg-video-intel/+question/89714)

[Nvidia Dual Displays not being detected](http://askubuntu.com/questions/103317/nvidia-dual-displays-not-being-detected)

...and once the previous links got me to where I was going, these two links: [Blank screen after installing nvidia restricted driver](http://askubuntu.com/questions/41681/blank-screen-after-installing-nvidia-restricted-driver) and [No second monitor and other problems](http://askubuntu.com/questions/288541/13-04-nvidia-geforce-8800-gts-no-second-monitor-and-other-problems) provided me with the following code which solved my mess:


