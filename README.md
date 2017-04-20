# STM32F7 HAL

This project, available from [GitHub](https://github.com/xpacks/stm32f7-hal),
includes the STM32F7 HAL files.

## Version

* CMSIS Pack v2.9.0
* ST HAL v1.2.0

## Documentation

The latest STM documentation is available from
[STM32CubeF7](http://www.st.com/web/catalog/tools/FM147/CL1794/SC961/SS1743/LN1897/PF261909).

The latest CMSIS documentation is available from
[keil.com](http://www.keil.com/cmsis).

The list of latest packs is available from [keil.com](https://www.keil.com/dd2/pack/).

## Original files

The original files are available in the `originals` branch.

These files were extracted from `Keil.STM32F7xx_DFP.2.9.0.pack`.

To save space, only the following folders were preserved:

* Drivers/STM32F\?xx\_HAL\_Driver/

## Changes

* `stm32f7xx_hal.h`: silence `-Wpadded`.

## Tests

```
export PATH=/usr/local/gcc-arm-none-eabi-5_2-2015q4/bin:$PATH
bash ../../../scripts/run-tests.sh
```
