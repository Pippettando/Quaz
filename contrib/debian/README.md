
Debian
====================
This directory contains files used to package quazd/quaz-qt
for Debian-based Linux systems. If you compile quazd/quaz-qt yourself, there are some useful files here.

## quaz: URI support ##


quaz-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install quaz-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your quaz-qt binary to `/usr/bin`
and the `../../share/pixmaps/quaz128.png` to `/usr/share/pixmaps`

quaz-qt.protocol (KDE)

