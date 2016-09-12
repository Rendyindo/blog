---
title:  "sdat2img For Android"
categories: 
  - Tool
tags:
  - sdat2img
---

**sdat2img for Android!**

Most of us, have no pc for converting
 system.new.dat to system.img...

So, this is why i create this tool!


sdat2img is a tool, that write on python language, to convert system.new.dat into system.img

This tool was only work on Windows and Linux

So i adapt it into android that can be runned in the Terminal

**Requirements:**

* Custom Recovery
* Around 30-50MB of free system
* a Terminal


**Installation:**

* Download the zip
* Install via custom recovery
* Reboot!


**Uninstalling:**
I should have the uninstaller, but it is gone somewere in my PC. So maybe later gonna add this.

**Download links:**
[AndroidFileHost]("https://www.androidfilehost.com/?fid=24686681827313070")

Well, this is pretty simple, haha.
Just like the xpirt sdat2img.

`Usage: sdat2img <system_transfer_list> <system_new_file> <system_img>`

And wait for the process finish.

**WARNING!
I SUGGEST YOU TO "cd" TO THE DIRECTORY OF system.new.dat FIRST!**

**How to extract the system.img?**

Just simply enter this command
Dont forget to "cd" to the directory of system.img

    mkdir system
    mount -t ext4 -o loop system.img system
    cp -rf system system2 

And the output is on system2 folder.
Dont forget to press enter each command you type!


**Changelog:**
**0.2 BETA**
    
    [Fixed] Convert error
    

Old Changelog
    
    **0.1 BETA**
    - Intial Release


**Credits:**

* @xpirt for sdat2img.py
* @7175 for python for android

[XDA Thread]("http://forum.xda-developers.com/android/software-hacking/tool-sdat2img-android-t3448797/page1")
