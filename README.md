# dirty-plex-embedded
A dirty Plex Embedded build upon LibreElec 9


Since PMP Embedded is using an outdated kernel and Plex seems to have no plans to upgrade, I have created a dirty image my self. Only use this if you want to use hardware which is not supported supported with the official release!

I would also be interested if HW decoding is working for you guys.

To Install:

Create an USB with the latest official nightly
Delete and replace the two Files on the USB drive provided in the Download

When the USB drive starts live boot enter tty3 by pressing ctrl+alt+F3 and enter these commands

systemctl stop kodi
installer

If the network is not up on the first start just press retry, after that PMP should actually wait for your network to come online.

I hope I could help someone with this.
