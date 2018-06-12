
Debian
====================
This directory contains files used to package securecloudcoind/securecloudcoin-qt
for Debian-based Linux systems. If you compile securecloudcoind/securecloudcoin-qt yourself, there are some useful files here.

## securecloudcoin: URI support ##


securecloudcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install securecloudcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your securecloudcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/securecloudcoin128.png` to `/usr/share/pixmaps`

securecloudcoin-qt.protocol (KDE)

