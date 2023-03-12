# ZMK firmware for the Mini M using the MiniRazz controller

This is a demo zmk-config repository to show how to build zmk firmware for the Unicomp Mini M keyboard using the open hardware replacement controller "MiniRazz".
The controller that this firmware is for can be found here:
https://github.com/purdeaandrei/MiniRazz

A firmware with the default keymap can be downloaded on the releases page of this repository.

The keymap can be customized by forking this repository, and editing the keymap. The firmware will be automatically rebuilt by github, and will be available on
the "Actions" tab of the forked repository. If you want to keep your keymap secret, you can copy the content of this repository into a private github repository.

Building locally is possible if you clone the `git@github.com:purdeaandrei/zmk.git` repository, and check out the `minirazz_history_may_change` branch.
Please follow ZMK documentation for details on how to build locally.

# License

The files in this repository are licensesd under MIT.

Some dependencies pulled in automatically by the 'west' tool have difference licenses.
- ZMK is under MIT
- Zephyr OS is under Apache 2.0
- Raspberry Pi Pico HAL is under BSD 3-Clause license


