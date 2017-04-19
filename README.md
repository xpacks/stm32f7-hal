# STM32F7 HAL

This project, available from [GitHub](https://github.com/xpacks/stm32f7-hal),
includes the STM32F7 HAL files.

## Version

* v1.5.0

## Documentation

The latest STM documentation is available from
[STM32CubeF7](http://www.st.com/web/catalog/tools/FM147/CL1794/SC961/SS1743/LN1897/PF261909).

## Original files

The original files are available in the `originals` branch.

These files were extracted from `stm32cube_fw_f7_v150.zip`.

To save space, only the following folder was copied:

* STM32Cube\_FW\_*/Drivers

and from it, the following folders/files were removed:

* all non-portable *.exe files
* Drivers/BSP/
* Drivers/CMSIS/
* Drivers/STM32F?xx\_HAL\_Driver/*.chm

## Changes

* `stm32f7xx\_hal.h`: silence `-Wpadded`.

## Tests

```
export PATH=/usr/local/gcc-arm-none-eabi-5_2-2015q4/bin:$PATH
bash ../../../scripts/run-tests.sh
```
