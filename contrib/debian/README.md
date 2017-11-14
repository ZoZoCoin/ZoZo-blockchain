
Debian
====================
This directory contains files used to package dtmid/dtmi-qt
for Debian-based Linux systems. If you compile dtmid/dtmi-qt yourself, there are some useful files here.

## dtmi: URI support ##


dtmi-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dtmi-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dtmi-qt binary to `/usr/bin`
and the `../../share/pixmaps/dtmi128.png` to `/usr/share/pixmaps`

dtmi-qt.protocol (KDE)

