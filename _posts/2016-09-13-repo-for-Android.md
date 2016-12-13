---
title:  "repo for Android"
categories: 
  - Tool
tags:
  - repo
  - build
  - rom
---

#  **repo for Android!** 

Just go to the point.

 ** Why did i make this? **
> Well, i don't have any laptop, so i try to find a way, to do repo sync without any laptop, and then i move the files to my PC, and then build it!

## Requirements

1. [Termux App](https://play.google.com/store/apps/details?id=com.termux&hl=ms&referrer=utm_source%3Dgoogle%26utm_medium%3Dorganic%26utm_term%3Dtermux&pcampaignid=APPU_1_cNtPWNjBBIjsvAS03LboDw)
2. Internet Connection

### How to Install
#### Manual way

- Install some binaries
```
apt update
apt install python2
apt install curl
apt install git
```
- Setup git
> Please refer to [here](https://help.github.com/articles/set-up-git/)
- Install repo
```
mkdir ~/bin
curl http://github.com/Rendyindo/repo-installer/raw/master/repo > ~/bin
curl http://github.com/Rendyindo/repo-installer/raw/master/shrepo > /data/data/com.termux/files/usr/bin/repo
chmod +x ~/bin/repo
chmod +x /data/data/com.termux/files/usr/bin/repo
```
- Done!
#### Automatic way
- Download [this](http://github.com/Rendyindo/repo-installer/raw/master/installer-android.sh)

- Run that script on Termux via:
```
./installer-android.sh
```
The script will automatically download all binaries needed and install it.

And you are ready to go! have fun with repo!
Here are some screenshots:
![](https://github.com/Rendyindo/blog/raw/master/images/Screenshot_2016-12-12-05-30-43.png)
![](https://github.com/Rendyindo/blog/raw/master/images/Screenshot_2016-12-13-20-30-44.png)

