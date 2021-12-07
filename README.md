[xde-theme-airforce -- read me first file.  2021-12-06]: #

xde-theme-airforce
===============

Package `xde-theme-airforce-1.1.15` was released under CCPL:cc-by-nc-nd-3.0
license 2021-12-06.

This is a theme and a set of backgrounds for the _XDE (X Desktop
Environment)_ that provides a set of backgrounds on
a Airforce theme.
This theme uses the Squared-green style from the [`xde-styles`][11]
package.

The source for `xde-theme-airforce` is hosted on [GitHub][1].


Release
-------

This is the `xde-theme-airforce-1.1.15` package, released 2021-12-06.
This release, and the latest version, can be obtained from [GitHub][1],
using a command such as:

    $> git clone https://github.com/bbidulock/xde-theme-airforce.git

Please see the [RELEASE][3] and [NEWS][4] files for release notes and
history of user visible changes for the current version, and the
[ChangeLog][5] file for a more detailed history of implementation
changes.  The [TODO][6] file lists features not yet implemented and
other outstanding items.

Please see the [INSTALL][8] file for installation instructions.

When working from `git(1)`, please use this file.  An abbreviated
installation procedure that works for most applications appears below.

This release is published under CCPL:cc-by-nc-nd-3.0 (primarily because
the base styles used to develop these styles were licensed under this
license).
Please see the license in the file [COPYING][10].


Quick Start
-----------

The quickest and easiest way to get `xde-theme-airforce` up and
running is to run the following commands:

    $> git clone https://github.com/bbidulock/xde-theme-airforce.git
    $> cd xde-theme-airforce
    $> ./autogen.sh
    $> ./configure
    $> make
    $> make DESTDIR="$pkgdir" install

This will configure, compile and install `xde-theme-airforce` the
quickest.  For those who like to spend the extra 15 seconds reading
`./configure --help`, some compile time options can be turned on and off
before the build.

For general information on GNU's `./configure`, see the file
[INSTALL][8].


Prerequisites
-------------

This package needs the [`xde-styles`][11] package to be useful and also
requires the `xde-setbg(1)` program from the [`xde-ctools`][12] package.


Issues
------

Report issues on GitHub [here][2].


Samples
-------

Following are the twelve wallpapers included in the theme:

![emeraldcoast.jpg](images/emeraldcoast.jpg "Wallpaper #1")
![f22_missle_shower.jpg](images/f22_missle_shower.jpg "Wallpaper #2")
![f22_wing_formation.jpg](images/f22_wing_formation.jpg "Wallpaper #3")
![f35_cockpit.jpg](images/f35_cockpit.jpg "Wallpaper #4")
![f35_crater.jpg](images/f35_crater.jpg "Wallpaper #5")
![fighterjets.jpg](images/fighterjets.jpg "Wallpaper #6")
![following.jpg](images/following.jpg "Wallpaper #7")
![landing.jpg](images/landing.jpg "Wallpaper #8")
![mig_banking.jpg](images/mig_banking.jpg "Wallpaper #9")
![overalaska.jpg](images/overalaska.jpg "Wallpaper #10")
![squad.jpg](images/squad.jpg "Wallpaper #11")
![thunderbird.jpg](images/thunderbird.jpg "Wallpaper #12")

[1]: https://github.com/bbidulock/xde-theme-airforce
[2]: https://github.com/bbidulock/xde-theme-airforce/issues
[3]: https://github.com/bbidulock/xde-theme-airforce/blob/master/RELEASE
[4]: https://github.com/bbidulock/xde-theme-airforce/blob/master/NEWS
[5]: https://github.com/bbidulock/xde-theme-airforce/blob/master/ChangeLog
[6]: https://github.com/bbidulock/xde-theme-airforce/blob/master/TODO
[7]: https://github.com/bbidulock/xde-theme-airforce/blob/master/COMPLIANCE
[8]: https://github.com/bbidulock/xde-theme-airforce/blob/master/INSTALL
[9]: https://github.com/bbidulock/xde-theme-airforce/blob/master/LICENSE
[10]: https://github.com/bbidulock/xde-theme-airforce/blob/master/COPYING
[11]: https://github.com/bbidulock/xde-styles
[12]: https://github.com/bbidulock/xde-ctools

[ vim: set ft=markdown sw=4 tw=72 nocin nosi fo+=tcqlorn spell: ]: #
