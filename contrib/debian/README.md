
Debian
====================
This directory contains files used to package nanucoind/nanucoin-qt
for Debian-based Linux systems. If you compile nanucoind/nanucoin-qt yourself, there are some useful files here.

## nanucoin: URI support ##


nanucoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nanucoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nanucoinqt binary to `/usr/bin`
and the `../../share/pixmaps/nanucoin128.png` to `/usr/share/pixmaps`

nanucoin-qt.protocol (KDE)

