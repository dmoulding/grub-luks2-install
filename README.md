# grub-luks2-install
Install GRUB with LUKS2 support

** NOTICE: The latest version of GRUB (version 2.14 as of this writing) seem to have resolved all remaining issues with grub-install and LUKS 2, as well as GRUB now supports Argon2. For new versions of GRUB, grub-luks2-install is now unnecessary and, as such, this project has now reached its conclusion. **

Although GRUB (as of 2.06) supports unlocking LUKS2 volumes, it seems
grub-install doesn't fully support creating a core image that can
unlock them. This script is intended to simplify the process of
installing GRUB with LUKS2 support until such time as grub-install can
do it correctly and automatically.
