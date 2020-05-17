

it prints the any print string on UART0. As such, it can be used
easily with qemu, like

```sh
$ qemu-system-aarch64 -M raspi3 -kernel kernel8.img -serial stdio
my assignment was done
```
