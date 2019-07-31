# Nino

[![Get it on AppCenter](https://appcenter.elementary.io/badge.svg)](https://appcenter.elementary.io/com.github.torikulhabib.nino)

Nino is an internet speed monitor with a simple appearance.

Features:

* Small window application features.
* Alert when no internet connection is available.
* Many color theme choices are available.
* Lock position on the desktop.
* Save the position of the widget.
* The choice is always above the screen or below.

![screenshot](Screenshot.png)
![screenshot 1](Screenshot1.png)
![screenshot 2](Screenshot2.png)
![screenshot 3](Screenshot3.png)
![screenshot 4](Screenshot4.png)

## Building, Testing, and Installation

You'll need the following dependencies:

* meson
* libgranite-dev
* libgtop2-dev
* gtk+-3.0
* valac

Run `meson` to configure the build environment and then `ninja` to build and run automated tests

    meson build --prefix=/usr
    cd build
    ninja

To install, use `ninja install`, then execute with `com.github.torikulhabib.nino`

    sudo ninja install
    com.github.torikulhabib.nino
