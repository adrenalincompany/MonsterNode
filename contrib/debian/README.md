
Debian
====================
This directory contains files used to package monsternoded/monsternode-qt
for Debian-based Linux systems. If you compile monsternoded/monsternode-qt yourself, there are some useful files here.

## monsternode: URI support ##


monsternode-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install monsternode-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your monsternode-qt binary to `/usr/bin`
and the `../../share/pixmaps/monsternode128.png` to `/usr/share/pixmaps`

monsternode-qt.protocol (KDE)

