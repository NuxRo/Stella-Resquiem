# Stella-Resquiem
Rescue Live image based on CentOS 7 x86_64 Live media.

It includes loads of handy utils such as photorec, chntpw, megacli, r1soft and many more.

It's as easy to build as:
```
livecd-creator -f Stella-Resquiem-`date +%Y%m%d` -c Stella-Resquiem.cfg --tmpdir=/tmp/stella --logfile=LOGFILE.txt -v -d
```
You'll end up with an ISO in the working directory.

The kickstart is a bit stale, PRs welcome.

Download from http://li.nux.ro/download/ISO/Stella-Resquiem-7-x86_64.iso
