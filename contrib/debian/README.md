
Debian
====================
This directory contains files used to package securityxd/securityx-qt
for Debian-based Linux systems. If you compile securityxd/securityx-qt yourself, there are some useful files here.

## securityx: URI support ##


securityx-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install securityx-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your securityxqt binary to `/usr/bin`
and the `../../share/pixmaps/securityx128.png` to `/usr/share/pixmaps`

securityx-qt.protocol (KDE)

