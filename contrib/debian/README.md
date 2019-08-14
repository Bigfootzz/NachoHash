
Debian
====================
This directory contains files used to package nachohashd/nachohash-qt
for Debian-based Linux systems. If you compile nachohashd/nachohash-qt yourself, there are some useful files here.

## nachohash: URI support ##


nachohash-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nachohash-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nachohashqt binary to `/usr/bin`
and the `../../share/pixmaps/nachohash128.png` to `/usr/share/pixmaps`

nachohash-qt.protocol (KDE)

