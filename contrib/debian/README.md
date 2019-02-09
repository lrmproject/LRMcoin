
Debian
====================
This directory contains files used to package lrmcoind/lrmcoin-qt
for Debian-based Linux systems. If you compile lrmcoind/lrmcoin-qt yourself, there are some useful files here.

## lrmcoin: URI support ##


lrmcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install lrmcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your lrmcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/lrmcoin128.png` to `/usr/share/pixmaps`

lrmcoin-qt.protocol (KDE)

