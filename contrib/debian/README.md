
Debian
====================
This directory contains files used to package zozocoind/zozocoin-qt
for Debian-based Linux systems. If you compile zozocoind/zozocoin-qt yourself, there are some useful files here.

## zozocoin: URI support ##


zozocoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zozocoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zozocoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/zozocoin128.png` to `/usr/share/pixmaps`

zozocoin-qt.protocol (KDE)

