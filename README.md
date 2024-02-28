# Padavan QMK firmware
*A Minivan keyboard with small numpad and wireless capabilities.*  

IMPORTANT: This firmware is only suitable for wired use.
If you would like to use the wireless version, you'll need to use the [ZMK firmware](https://github.com/kilipan/zmk-config-padavan).

* Keyboard Maintainer: [kilipan](https://github.com/kilipan)
* Hardware Supported: *Padavan keyboard with Pro-Micro-ish Controller*
* Hardware Availability: [*production files*](https://github.com/kilipan/padavan)

Make example for this keyboard (after setting up your build environment):

    make padavan:default

Flashing example for this keyboard:

    make padavan:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Default keymap
The `default` keymap is set to QWERTY.
Please consult the [keymap file](https://github.com/kilipan/qmk-config-padavan/tree/main/keymaps/default/keymap.c) for further details.

## Vial support
Ready-to-flash Vial firmware is provided as `padavan_vial.uf2`.

If you want to compile the Vial firmware yourself, you may use `make padavan:vial` in your `vial-qmk` directory.
Also see [the `vial` keymap directory](https://github.com/kilipan/qmk-config-padavan/tree/main/keymaps/vial).
For further details please consult the [Vial docs](https://get.vial.today/docs/porting-to-vial.html#1-prepare-your-build-environment).
