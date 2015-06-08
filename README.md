# aur
My Arch Linux AUR packages

##DEPRECATED: all packages migrated to AUR4

* create packages https://wiki.archlinux.org/index.php/Makepkg
* upload to https://aur.archlinux.org/pkgsubmit.php

```sh
### generate md5
makepkg -g

### clean out leftover files and folders
makepkg -c

### install
makepkg -i

### prepare upload file for AUR
## install pkgbuild-introspection-git
mkaurball
```
