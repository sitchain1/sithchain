
Debian
====================
This directory contains files used to package sithchaind/sithchain-qt
for Debian-based Linux systems. If you compile sithchaind/sithchain-qt yourself, there are some useful files here.

## sithchain: URI support ##


sithchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sithchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sithchain-qt binary to `/usr/bin`
and the `../../share/pixmaps/sithchain128.png` to `/usr/share/pixmaps`

sithchain-qt.protocol (KDE)

