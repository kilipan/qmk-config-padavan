# padavan

![padavan](imgur.com image replace me!)

*A minivan keyboard with small numpad and wireless capabilities.*

* Keyboard Maintainer: [kilipan](https://github.com/kilipan)
* Hardware Supported: Supports any pro-micro compatible controller, includinge `nice!nano` for wireless capabilities!
* Hardware Availability: Will be made available in time.

Make example for this keyboard (after setting up your build environment):

    make padavan:default

Flashing example for this keyboard:

    make padavan:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
