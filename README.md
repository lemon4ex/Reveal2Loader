### Reveal2Loader
Dynamically loads Reveal v4(8796) into applications and plugins.

### Problem in iOS11
The iOS11 jailbroken device does not take effect after installing Reveal2Loader. Because the dlopen function fails to load the RevealServer dynamic library. The error is as follows
> file system sandbox blocked mmap() '/Library/Frameworks/RevealServer.framework/RevealServer'

This code compatible with iOS11 jailbroken device now.

![QQ20190219-050112@2x.png](https://github.com/lemon4ex/Reveal2Loader/blob/master/QQ20190219-050112@2x.png)

### Thanks
* original version: https://github.com/zidaneno5/Reveal2Loader
