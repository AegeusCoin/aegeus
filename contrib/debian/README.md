
Debian
====================
This directory contains files used to package aegeusd/aegeus-qt
for Debian-based Linux systems. If you compile aegeusd/aegeus-qt yourself, there are some useful files here.

## aegeus: URI support ##


aegeus-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install aegeus-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your aegeusqt binary to `/usr/bin`
and the `../../share/pixmaps/aegeus128.png` to `/usr/share/pixmaps`

aegeus-qt.protocol (KDE)

