This repository is an example of creating a USB device with an STM32 board. The used USB stack is TinyUSB, instead of the ST's own USB middleware. Blog post explaining the repository can be found from here:
https://ejaaskel.dev/making-usb-device-with-stm32-tinyusb/

The example code is from TinyUSB, from the CDC Dual Ports device example.
https://github.com/hathach/tinyusb/tree/master/examples/device/cdc_dual_ports

The steps to integrate the TinyUSB to the STM32CubeIde project follow this GitHub answer:
https://github.com/hathach/tinyusb/discussions/633#discussioncomment-342237
