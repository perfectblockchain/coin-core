
Debian
====================
This directory contains files used to package rizcoind/rizcoin-qt
for Debian-based Linux systems. If you compile rizcoind/rizcoin-qt yourself, there are some useful files here.

## rizcoin: URI support ##


rizcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rizcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rizcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/rizcoin128.png` to `/usr/share/pixmaps`

rizcoin-qt.protocol (KDE)

