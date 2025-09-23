# gebeto9

![gebeto9](https://github.com/user-attachments/assets/bbdb1394-39ca-4d56-884f-1afab9752138)

*Simple basic numpad 3x3*

* Keyboard Maintainer: [gebeto](https://github.com/gebeto)
* Hardware Supported: *Handwire, rp2040*
* Hardware Availability: *Self made*

Make example for this keyboard (after setting up your build environment):

    make gebeto9:default

Flashing example for this keyboard:

    make gebeto9:default:flash

See the [build environment setup](https://docs.qmk.fm/#/getting_started_build_tools) and the [make instructions](https://docs.qmk.fm/#/getting_started_make_guide) for more information. Brand new to QMK? Start with our [Complete Newbs Guide](https://docs.qmk.fm/#/newbs).

## Bootloader

Enter the bootloader in 3 ways:

* **Bootmagic reset**: Hold down the key at (0,0) in the matrix (usually the top left key or Escape) and plug in the keyboard
* **Physical reset button**: Briefly press the button on the back of the PCB - some may have pads you must short instead
* **Keycode in layout**: Press the key mapped to `QK_BOOT` if it is available
