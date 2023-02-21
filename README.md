# Source code to build rtcwake application for Linux
- Add your own Makefile to build. To build for your desktop, use this command `gcc -o rtcwake rtcwake.c -I.` 
- Use below command to excute
```
rtcwake -m $(sleep_method) -s $(seconds)
```
Or call through `system()`
```
system("/root/rtcwake -m mem -s 10");
```
- More information about rtcwake: https://man7.org/linux/man-pages/man8/rtcwake.8.html
