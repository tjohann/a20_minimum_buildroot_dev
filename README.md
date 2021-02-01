Summary for setting up a minimum A20 device (Cortex-A7) image
=============================================================

This repository is my playground to setup a minimal image () which different components than "normally". The idea is to have only the linux kernel as fundament and all other parts are not mainstream.

I`m interested in embedded linux in general and so i decided to try it out, this is the playground for it.

Steps:
- use MUSL
- use OpenRC
- change to the sysklogd (https://github.com/troglobit/sysklogd/) like slackware (http://www.slackware.com)
- use toybox (https://landley.net/toybox/) instead of busybox (ox is used in android)
- then active SELinux (or appamor or SMACK), seccomp, namespaces and cgroups and see if such topics still work as expected
- ...


WARNING: This is work in progress! So it's possible that something is not working as expected.

If you face a bug then pls use https://github.com/tjohann/a20_minimum_buildroot_dev/issues to create an issue.


Description
-----------

Every step is documented here: ([The Documentation](buildroot_minimal_bananapi.md)).

Images of the different steps could be find here: https://sourceforge.net/projects/a20-minimum-buildroot


TODO
----

t.b.d.
