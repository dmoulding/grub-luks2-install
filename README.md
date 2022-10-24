# grub-luks2-install
Install GRUB with LUKS2 support

Although GRUB (as of 2.06) supports unlocking LUKS2 volumes, it seems
grub-install doesn't fully support creating a core image that can
unlock them. This script is intended to simplify the process of
installing GRUB with LUKS2 support until such time as grub-install can
do it correctly and automatically.
