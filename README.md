
# Windows Driver Submodule for LGE G8
> based on [SurfaceDuo-Drivers](https://github.com/WOA-Project/SurfaceDuo-Drivers/)
## [Here](https://github.com/woa-msmnile/msmnile-Drivers) is the Full Driver Pack.
<!-- ## ⚠ Remember to decompress Alpha-Drivers\components\QC8150\Graphics\qcdxwsaum.7z and put the image file into the Alpha-Drivers\components\QC8150\Graphics\GRAPHICS.SOC_QC8150.XXX_XXX_XXX/. -->
This repository contains driver binary files for LGE G8.
All driver binary files form a board support package to be used on LGE G8 devices to provide hardware support for the Windows operating system.

These driver files are not perfect, typos may exist, feel free to file an issue on GitHub in case you found any.

| Feature                | Notes                                               | Status         |
|------------------------|-----------------------------------------------------|----------------|
| Bluetooth              |                                                     | ✅            |
| Wifi                   |                                                     | ✅            |
| UFS                    |                                                     | ✅            |
| Touch                  |                                                     | ✅            |
| GPU                    | May not work on some devices with unofficial panel. | ✅            |
| Battery                |                                                     | ❌            |
| Buttons                |                                                     | ✅            |
| Sensors                |                                                     | ❌            |
| Haptic                 |                                                     | ❌            |
| Cellular Data          |                                                     | ❌            |
| Charge                 |                                                     | ❌            |

## Installation
Read [here](https://woa-msmnile.github.io/InstallationGuides/InstallDrivers.html) for Installation Guide.

# Tips
May have to remove the auddev driver in platform drivers and install the one provided here.