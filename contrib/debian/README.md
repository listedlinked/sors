
Debian
====================
This directory contains files used to package sorsd/sors-qt
for Debian-based Linux systems. If you compile sorsd/sors-qt yourself, there are some useful files here.

## sors: URI support ##


sors-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install sors-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your sorsqt binary to `/usr/bin`
and the `../../share/pixmaps/sors128.png` to `/usr/share/pixmaps`

sors-qt.protocol (KDE)

