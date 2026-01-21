# ZMK Config for HHBB Keyboard

This repository contains the custom [ZMK firmware](https://zmk.dev/) configuration for the HHBB keyboard.

## About ZMK

ZMK (Zephyr Mechanical Keyboard) is an open-source keyboard firmware built on the Zephyr RTOS. It provides modern features including Bluetooth connectivity, low power consumption, and highly customizable key mappings.

## About This Repository

This configuration builds custom firmware for the HHBB keyboard using a nice!nano v2 controller. The firmware is automatically built using GitHub Actions whenever changes are pushed to the repository.

## Keyboard Layout

The HHBB keyboard has the following matrix layout with array index values:

```
|-------------------------------------------------|
| 00 | 01 | 02 | 03 | 04 | 05 | 06 | 07 | 08 | 09 |
|-------------------------------------------------|
|  10 | 11 | 12 | 13 | 14 | 15 | 16 | 17 |   18   |
|-------------------------------------------------|
|  20   | 21 | 22 | 23 | 24 | 25 | 26 | 27 |  28  |
|-------------------------------------------------|
   | 30 | 31 |     32    |    33     | 34 | 35 |
   |-------------------------------------------|
```

## Building

The firmware is automatically built by GitHub Actions. You can find the compiled firmware files in the Actions tab after each successful build.

## Customization

To customize your keymap, edit the file: `config/boards/shields/hhbb/hhbb.keymap`

For more information on ZMK configuration, visit the [ZMK documentation](https://zmk.dev/docs).
