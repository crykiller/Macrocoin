
Debian
====================
This directory contains files used to package macrocoind/macrocoin-qt
for Debian-based Linux systems. If you compile macrocoind/macrocoin-qt yourself, there are some useful files here.

## macrocoin: URI support ##


macrocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install macrocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your macrocoinqt binary to `/usr/bin`
and the `../../share/pixmaps/macrocoin128.png` to `/usr/share/pixmaps`

macrocoin-qt.protocol (KDE)

