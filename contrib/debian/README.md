
Debian
====================
This directory contains files used to package qdpd/qdp-qt
for Debian-based Linux systems. If you compile qdpd/qdp-qt yourself, there are some useful files here.

## qdp: URI support ##


qdp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install qdp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your qdpqt binary to `/usr/bin`
and the `../../share/pixmaps/qdp128.png` to `/usr/share/pixmaps`

qdp-qt.protocol (KDE)

