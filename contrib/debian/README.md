
Debian
====================
This directory contains files used to package anterd/anter-qt
for Debian-based Linux systems. If you compile anterd/anter-qt yourself, there are some useful files here.

## anter: URI support ##


anter-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install anter-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your anterqt binary to `/usr/bin`
and the `../../share/pixmaps/anter128.png` to `/usr/share/pixmaps`

anter-qt.protocol (KDE)

