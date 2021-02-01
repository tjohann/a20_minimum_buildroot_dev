Summary for settin up a minimum A20 device (Cortex-A7) image
============================================================

This repository is my playground to setup a minimum image which is more or less GPL/LGPL or related license free. The idea is to have only the linux kernel as GPL and all other parts are with more permissive license.

I got a lot of questions about that topic, so i decided to try it out, this is the playground for it.

Steps:
- i want to use MUSL, runit, socklog and toybox for the basic system.
- then active SELinux (or appamor or SMACK), seccomp, namespaces and cgroups


WARNING: This is work in progress! So it's possible that something is not working as expected.

If you face a bug then pls use https://github.com/tjohann/a20_minimum_buildroot_dev/issues to create an issue.


Description
-----------

Every step is documented here: ([The Documentation](buildroot_minimal_bananapi.md)).

Images of the different steps could be find here: https://sourceforge.net/projects/a20-minimum-buildroot


TODO
----

t.b.d.
