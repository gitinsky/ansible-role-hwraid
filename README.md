# Hwraid role

Designed for ubuntu, could be easily updated to support debian.

You might also like to install new [smartmontools](https://github.com/gitinsky/ansible-role-smartmontools) (seems to be 6.4 or later) with aacraid driver support.

Installs packages from [hwraid.le-vert.net](http://hwraid.le-vert.net/wiki/DebianPackages).

Set ```hwraid_target``` to one of the following values:

- 3Ware
- Adaptec
- SmartArray
- MegaIDE
- FusionMPT
- FusionMPT_SAS2
- MegaRAID
- MegaRAID_SAS
- MegaRAID_Dell
