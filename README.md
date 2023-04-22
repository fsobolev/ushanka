<p><img src="ushanka.png" width=128px align="left"><h1>Ushanka</h1>

Custom Fedora Silverblue image</p>

<br/>

[![build-ushanka](https://github.com/fsobolev/ushanka/actions/workflows/build.yml/badge.svg)](https://github.com/fsobolev/ushanka/actions/workflows/build.yml)

Many thanks to [Universal Blue](https://github.com/ublue-os) project for providing a way to create custom Silverblue images. Most of files in this repo are from [ublue-os/main](https://github.com/ublue-os/main) (some are slightly modified).

List of changes (compared to ublue-os/main):
* Only Silverblue (GNOME) images are created
* Removed some CLI apps, Firefox, GNOME Terminal, Totem video thumbnailer (ffmpeg thumbnailer is used instead), GNOME Background Logo extension
* Added GNOME Console, nautilus-python, Micro text editor, adw-gtk3 theme and a few development tools: dotnet7, gettext, itstool, glib2-devel, blueprint-compiler

This image is created for my personal needs, but feel free to use it if it fits yours :blush:

---

[Ushanka](https://en.wikipedia.org/wiki/Ushanka) is a winter hat.

[ushanka.png](ushanka.png) is based on [this image](https://commons.wikimedia.org/wiki/File:Russia_Countryball.png) available under CC BY-SA 4.0.
