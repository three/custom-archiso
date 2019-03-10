# Custom Arch ISO

This repository contains an [archiso][0] profile containing a superset of
features from the baseline, as well as additional tools I use to install and
debug Arch Linux installations. For instance, a graphical environment and web
browser. Expect the result to be significantly larger than a normal installation
iso. My goal is to have the result fit on a 16GB flash drive.

Before running `./build.sh`, copy all files and change their ownership to root.
Then run the build script from that location (as root).

## LICENSE

This profile is based off releng from archiso which, as far as I can tell, is
licensed under GPL.

[0]: https://wiki.archlinux.org/index.php/archiso
