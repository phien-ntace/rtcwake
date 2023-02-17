# Source code to build rtcwake application for Embedded Linux
- Add your own Makefile to build
- Use below command to excute
```
rtcwake -m $(sleep_method) -s $(seconds)
```
Or call through `system()`
```
system("/root/rtcwake -m mem -s 10");
```
- More information about rtcwake: https://man7.org/linux/man-pages/man8/rtcwake.8.html
