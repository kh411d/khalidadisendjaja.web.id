---
categories:
- Internet &amp; Tech
date: 2014-02-19T14:55:27Z
date_gmt: 2014-02-19 07:55:27 +0700
tags: []
title: '[NOTE] Upgrade NodeJS lokal via NPM dan "n" module'
url: /2014/02/19/note-upgrade-nodejs-lokal-via-npm-dan-n-module/
---

**Sebelum NodeJS-nya di-upgrade, cek dulu versi yang ter-install,**

 
    $node -v
    v0.10.12

**Bersih2x NPM Cache,**

 
    sudo npm cache clean -f

**Install "n" [Node binary manager](https://github.com/visionmedia/n) ,**

 
    sudo npm install -g n

**Upgrade Node ke versi terakhir,**

 
    sudo n 0.10.26

**Atau bisa langsung upgrade ke versi stable terakhir,**

 
    sudo n stable

**Cek versi node yg telah terupgrade,**

 
    $node -v
    v0.10.26