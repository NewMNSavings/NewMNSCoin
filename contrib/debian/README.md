
Debian
====================
This directory contains files used to package nmnscd/nmnsc-qt
for Debian-based Linux systems. If you compile nmnscd/nmnsc-qt yourself, there are some useful files here.

## nmnsc: URI support ##


nmnsc-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nmnsc-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nmnsc-qt binary to `/usr/bin`
and the `../../share/pixmaps/pivx128.png` to `/usr/share/pixmaps`

nmnsc-qt.protocol (KDE)

