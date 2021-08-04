### Reveal2Loader

Dynamically loads Reveal into applications and plugins.

This package uses the RevealServer.framework of Reveal v21(11690) , you can replace it to what you want.

Compatible with `iOS8 ~ iOS14` jailbroken device.

### Problem in iOS11 ~ iOS12

The iOS11 ~ iOS12 jailbroken device does not take effect after installing Reveal2Loader. Because the dlopen function fails to load the RevealServer dynamic library. The error is as follows

> file system sandbox blocked mmap() '/Library/Frameworks/RevealServer.framework/RevealServer'

This code fixed it now.

![QQ20190321-000639@2x.png](https://github.com/lemon4ex/Reveal2Loader/blob/master/QQ20190321-000639@2x.png)
![QQ20190219-050112@2x.png](https://github.com/lemon4ex/Reveal2Loader/blob/master/QQ20190219-050112@2x.png)
![QQ20190321-002625@2x.png](https://github.com/lemon4ex/Reveal2Loader/blob/master/QQ20190321-002625@2x.png)
![QQ20200602-023543@2x.png](https://github.com/lemon4ex/Reveal2Loader/blob/master/QQ20200602-023543@2x.png)

### Cydia Repo

https://repo.h4ck1n.com

### Thanks

- original version: https://github.com/zidaneno5/Reveal2Loader
