no-systemd
==========

This is an overlay with profiles to prevent systemd installation accidentally.
It masks systemd and a number of related packages, and sets systemd related
useflags to permanently disabled.

If you want to use it, the no-systemd.xml file contains a layman overlay
configuration and would just need to be dropped into /etc/layman/overlays/ on
a system with layman installed to make the overlay available in layman.
