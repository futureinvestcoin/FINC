
Debian
====================
This directory contains files used to package fincd/finc-qt
for Debian-based Linux systems. If you compile fincd/finc-qt yourself, there are some useful files here.

## finc: URI support ##


finc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install finc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your fincqt binary to `/usr/bin`
and the `../../share/pixmaps/finc128.png` to `/usr/share/pixmaps`

finc-qt.protocol (KDE)

