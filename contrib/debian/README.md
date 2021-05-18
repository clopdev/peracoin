
Debian
====================
This directory contains files used to package peracoind/peracoin-qt
for Debian-based Linux systems. If you compile peracoind/peracoin-qt yourself, there are some useful files here.

## peracoin: URI support ##


peracoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install peracoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your peracoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitcoin128.png` to `/usr/share/pixmaps`

peracoin-qt.protocol (KDE)

