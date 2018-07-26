# WIP: Linux ALSA module for Audient iD14

```bash
# build the module using the kernel build system
KERNELDIR=~/Products/cm/linux-stable/ make 
# tail kernel output
sudo dmseg -w
# insert module into kernel
insmod hello.ko 
```

## To Do

### Adhere to Kernel coding standards

Please see ~/Products/cm/linux-stable/Documentation/development-process/4.Coding.rst


## Resources

* [Updated LDD3 examples](https://github.com/martinezjavier/ldd3)
* [How to: USB pen driver for Linux](https://opensourceforu.com/2011/10/usb-drivers-in-linux-1/)
* [Reverse engineering a USB sound card](http://kicherer.org/joomla/index.php/en/blog/38-reverse-engineering-a-usb-sound-card-with-midi-interface-for-linux)



