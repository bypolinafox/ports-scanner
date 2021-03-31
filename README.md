# Ports-scanner
### Util for scanning TCP and UDP ports.
### Usage:
- start your util: python <ip> <left_border> <right_border>
- right and left borders - for defining range of ports
- if you wanna scan a lot of ports (e.g. >100) you may need use "ulimit -S -n 10000" in your terminal. 10000 or more, if you have an 24 Errno.
