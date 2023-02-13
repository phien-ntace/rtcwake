1. rtcwake source code for linux embedded
2. Add your Makefile to build.
3. Use it with follow command:
  rtcwake -m $(sleep_method) -s $(seconds)
Or use system command such as:
  system("/root/rtcwake -m mem -s 10");
4. More information about rtcwake: https://man7.org/linux/man-pages/man8/rtcwake.8.html
