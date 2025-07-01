# squeezeos-avocado-poky-src-mirror
source mirror with some files required by the squeezeos poky build process

you might want to use the provided docker-compose.yml file to host the files locally for
https://github.com/frostworx/squeezeos-avocado

this project is meant as a temporary solution until there is no "official" community url hosting those files.

the files included are either
 - no longer available upstream
 - complicated/impossible to download in an ancient linux distro (ssl problems)
 - don't have a valid home

most of the files were pulled from a different source (checksum unchanged, see commit #1 in the [squeezeos-avocado project](https://github.com/frostworx/squeezeos-avocado)),
the two openmoko tarballs were completely dead and were replaced with a git snapshot of the original opkg/opkg-utils projects

only files not pulling from the provided source urls and required for compiling baby firmware were added to the archive.
chances are VERY high that other files in [poky/meta/conf/checksums.ini](https://github.com/frostworx/squeezeos-avocado/blob/public/9.0/poky/meta/conf/checksums.ini)
are dead as well.


