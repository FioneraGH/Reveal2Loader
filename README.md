### Reveal2Loader
Dynamically loads Reveal into applications and plugins.

This package uses the RevealServer.framework of Reveal v24(12917) , you can replace it to what you want.

### Problem in iOS11 ~ iOS12
The iOS11 ~ iOS12 jailbroken device does not take effect after installing Reveal2Loader.
Because the dlopen function fails to load the RevealServer dynamic library. The error is as follows
> file system sandbox blocked mmap() '/Library/Frameworks/RevealServer.framework/RevealServer'

This code fixed it now, compatible with `iOS8 ~ iOS13` jailbroken device.

### Thanks
* original version: https://github.com/zidaneno5/Reveal2Loader
