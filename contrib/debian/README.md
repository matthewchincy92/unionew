
Debian
====================
This directory contains files used to package uniod/unio-qt
for Debian-based Linux systems. If you compile uniod/unio-qt yourself, there are some useful files here.

## unio: URI support ##


unio-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install unio-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your unio-qt binary to `/usr/bin`
and the `../../share/pixmaps/unio128.png` to `/usr/share/pixmaps`

unio-qt.protocol (KDE)

