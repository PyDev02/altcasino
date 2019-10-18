
Debian
====================
This directory contains files used to package ALTCd/ALTC-qt
for Debian-based Linux systems. If you compile ALTCd/ALTC-qt yourself, there are some useful files here.

## ALTC: URI support ##


ALTC-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ALTC-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ALTC-qt binary to `/usr/bin`
and the `../../share/pixmaps/ALTC128.png` to `/usr/share/pixmaps`

ALTC-qt.protocol (KDE)
