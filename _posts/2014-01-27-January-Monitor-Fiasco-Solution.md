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

[HOW TO FIX ERROR "THE SYSTEM IS RUNNING IN LOW-GRAPHICS MODE" ?](http://www.techlw.com/2012/12/how-to-fix-error-system-is-running-in.html)

[INSTALL NVIDIA DRIVERS ON UBUNTU 12.04 PRECISE/UBUNTU 11.10 ONEIRIC/LINUX MINT](http://www.techlw.com/2012/03/install-nvidia-drivers-on-ubuntu-1204.html)

[Ubuntu 13.04 "The system is running in low-graphics mode" error?](http://wyldeplayground.net/ubuntu-13-04-the-system-is-running-in-low-graphics-mode-error/)



[Dual monitor problem: larger screen is stuck at lower than maximum resolution](http://ubuntuforums.org/showthread.php?t=2074912)

code: [Fullscreen secondary monitor nvidia](http://pastebin.com/mcweUUZm)

[Can't see display at all!](https://answers.launchpad.net/ubuntu/+source/xserver-xorg-video-intel/+question/89714)

[Nvidia Dual Displays not being detected](http://askubuntu.com/questions/103317/nvidia-dual-displays-not-being-detected)

This one didn't work for me, but it's preserved here for posterity: [HOW TO FIX ERROR "THE SYSTEM IS RUNNING IN LOW-GRAPHICS MODE"?](http://www.techlw.com/2012/12/how-to-fix-error-system-is-running-in.html)

[How to fix “The system is running in low-graphics mode” error?](http://askubuntu.com/questions/141606/how-to-fix-the-system-is-running-in-low-graphics-mode-error)

[Ubuntu 13.10 freezing and low graphics mode](http://askubuntu.com/questions/384905/ubuntu-13-10-freezing-and-low-graphics-mode)

[Is my graphics card in use or not?](http://askubuntu.com/questions/364033/is-my-graphics-card-in-use-or-not)

[Install NVIDIA GeForce driver in Ubuntu 13.10 / 13.04 / 12.10 / 12.04 using PPA](http://www.howopensource.com/2012/10/install-nvidia-geforce-driver-in-ubuntu-12-10-12-04-using-ppa/)

[How to fix “The system is running in low-graphics mode” error?](http://ozkaya84.wordpress.com/2013/03/30/how-to-fix-the-system-is-running-in-low-graphics-mode-error/)

[How to fix “The system is running in low-graphics mode” error?](http://askubuntu.com/questions/141606/how-to-fix-the-system-is-running-in-low-graphics-mode-error)

[How to Install Nvidia Drivers](http://askubuntu.com/questions/61396/how-to-install-nvidia-drivers/61433#61433)

...and once the previous links got me to where I was going, these two links: [Blank screen after installing nvidia restricted driver](http://askubuntu.com/questions/41681/blank-screen-after-installing-nvidia-restricted-driver) and [No second monitor and other problems](http://askubuntu.com/questions/288541/13-04-nvidia-geforce-8800-gts-no-second-monitor-and-other-problems) provided me with the following code which solved my mess:

First I needed to check on which graphics card I had installed, and I used this command:
    
    glxinfo | grep OpenGL



    jkdhfgldfkjghlsdfjkgh
    ldsfkjghlsdkfjgh
    sd;lfkgh;df

[Ubuntu Bumblebee Project](https://wiki.ubuntu.com/Bumblebee)

