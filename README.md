osx-on-linux
============

This project contains configurations, scripts, and guides to help you make your
Linux desktop environment feel more like OS X. This involves changing keyboard
shortcuts, look and feel tweaks, and other items.

This is a work in progress, based on my Fedora 25 + Wayland desktop.
Contributions for other distributions and other graphical compositors are
welcome.

GTK
---

The gtk dir contains a configuration theme for GTK 2 and GTK 3 that mimcs
OS X behaviors. Among the changes:

* Super key used most places that Alt or Ctrl would be used. For example,
  Super+C to copy text (not to fight aliens) and Super+V to paste.
* Super modifiers for moving the cursor, like Super+Left for begin-of-line.

DCONF
-----

The dconf-dumps directory contains dconf configuration dumps for various
tweaks, including key bindings. Example changes:

* Super+Left and Right to switch tabs in Terminal
* Super+Q to close the current Window (closest we can get to hard Quit)
