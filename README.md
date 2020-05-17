Tutorial 05 - UART0, PL011
==========================

This tutorial does the same as tutorial 04, but it prints the serial number on UART0. As such, it can be used
easily with qemu, like

```sh
$ qemu-system-aarch64 -M raspi3 -kernel kernel8.img -serial stdio
my assignment was done
```
