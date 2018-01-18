
Debian
====================
This directory contains files used to package cmosd/cmos-qt
for Debian-based Linux systems. If you compile cmosd/cmos-qt yourself, there are some useful files here.

## cmos: URI support ##


cmos-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install cmos-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your cmosqt binary to `/usr/bin`
and the `../../share/pixmaps/cmos128.png` to `/usr/share/pixmaps`

cmos-qt.protocol (KDE)

