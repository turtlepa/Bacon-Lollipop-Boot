##Project Structure:
* ramdisk - Current changes
    *	**ADD** the empty folders "data", "dev", "proc", "sys", and "system".
* boot.img - Last built image
* boot.img-kernel - The stock asop kernel
* boot.img-ramdisk.cipo.gz - The asop ramdisk

##Build Instructions:
*  Automatic:
    *   Run `./Pack.sh`
*  Manual:
    *  	Create empty folders "data", "dev", "proc", "sys", and "system" required for building
    *  	`cd` to the git folder
    *  	Run `./bin/mkboot boot boot.img`

	`mkbootimg` is from android source code.
