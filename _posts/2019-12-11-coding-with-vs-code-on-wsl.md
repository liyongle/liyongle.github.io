---
layout: post
title: Coding with VS Code on WSL
excerpt: "How to code with VS Code and WSL on Windows 10."
categories: [code]
modified: 2019-12-11
comments: true
---

# Coding with VS Code on WSL

## Install WSL on Company Laptop

1. Enable developer mode in  Windows 10

``` 
Win -> Settings -> Update & Security -> For developers -> Developer mode
```
2. Enable WSL (Windows Subsystem for Linux)
```
Win -> Search "Turn Windows Features on or off" -> Enable WSL
```
3. Search WSL in Microsfot Store and select linux distribution you like.

4. Install it and then Launch it.

Now you have Linux on your Windows 10!

## Config proxy for your git in your linux

```
vim ~/.gitconfig

[http]
        proxy = http://username:password@proxycn2.huawei.com:8080
        sslVerify = false
[https]
        proxy = https://username:password@proxycn2.huawei.com:8080
        sslVerify = false

```

**For password**
```
! --> %21    # --> %23    $ --> %24    & --> %26    ' --> %27

( --> %28    ) --> %29    * --> %2A    + --> %2B    , --> %2C

/ --> %2F    : --> %3A    ; --> %3B    = --> %3D    ? --> %3F

@ --> %40    [ --> %5B    ] --> %5D
```


## Config VS Code and WSL

Please refer to https://code.visualstudio.com/docs/remote/wsl. 
