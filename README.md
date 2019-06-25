# platformio-custom-board-test

Test to use new PlatformIO custom board feature.

New board currently not supported by mbed: Nucleo STM32L452RE

Board used for mbed base configuration: Nucleo STM32L432KC

The file `boards/nucleo_l452re_mbed.json` is the same as the `nucleo_l452re.json` already existing in platformio, just with `mbed` added to the list of supported frameworks.

Remark: Decided to move `PinNames.h` etc. to `boards` subdirectory instead of `src` to prevent compilation errors for other boards.
