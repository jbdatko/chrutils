chrutils
========

ChrUbuntu Utilities (scripts and such).

This is a collection of scripts that I found useful while hacking around
ChrUbuntu on the Samsung ARM Chromebook.  It's mainly small one/two liners to
automate routine tasks specific to this environment.

If you are already in ChrUbuntu, cloning this repo is probably the easiest.  To
get the repo in ChromeOS however, it's probably easiest to download the [zip
file](https://github.com/jbdatko/chrutils/archive/master.zip), extract it and
go.

chruboot
--------

chruboot is the ChrUbuntu partition selector.  It's meant for ChrUbuntu on the
Samsung ARM chromebook, so if you tried it with some other hardware, your
results may vary...

There are two ways to run it:
```
sh -e chruboot.sh chromeos
sh -e chruboot.sh chrubuntu
```

The argument passed in sets the active boot partition and it will take affect
on the next reboot.
