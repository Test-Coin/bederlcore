
Debian
====================
This directory contains files used to package bederld/bederl-qt
for Debian-based Linux systems. If you compile bederld/bederl-qt yourself, there are some useful files here.

## bederl: URI support ##


bederl-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bederl-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bederlqt binary to `/usr/bin`
and the `../../share/pixmaps/bederl128.png` to `/usr/share/pixmaps`

bederl-qt.protocol (KDE)

