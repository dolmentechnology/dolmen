
Debian
====================
This directory contains files used to package dolmend/dolmen-qt
for Debian-based Linux systems. If you compile dolmend/dolmen-qt yourself, there are some useful files here.

## dolmen: URI support ##


dolmen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dolmen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dolmen-qt binary to `/usr/bin`
and the `../../share/pixmaps/dolmen128.png` to `/usr/share/pixmaps`

dolmen-qt.protocol (KDE)

