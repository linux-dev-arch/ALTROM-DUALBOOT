# ALTROM-DUALBOOT
This is the repo offering the custom dual boot bootloader source code for ALTROM tested devices
## USAGE
* Clone both the [ALTROM](https://github.com/linux-dev-arch/ALTROM) and [DZO9](https://github.com/MediatekInfo/DZ09) repos.
* Copy the sd_loader_blob.h from ALTROM to DZO9/sources.
* Replace DZ09_boot.c with this repo's version.
* Take a backup using [mtk_dump](https://github.com/ilyakurdyukov/mediatek_flash).(Mandatory!).
* build using Embitz ide.
* Flash using DZ09 instructions.
* Switch between either os by pressing or releasing the 5 KEY (PRESS=ALTROM ,NO_PRESS=STOCK OS ).
* To undo changes flash original firmware dump using mtk_dump.
