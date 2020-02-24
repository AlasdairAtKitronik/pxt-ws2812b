# Kitronik fork of the WS2812B package for microbit

A driver for WS2812B programmable LEDs in MakeCode which respects the brightness in all scenarios.

## Usage

The package exposes ``ws2812b.sendBuffer`` that bit-bangs a color buffer for WS2812B LEDs over a pin.

See 
# Kitronik HaloHD 
https://github.com/KitronikLtd/pxt-kitronik-halohd
for an example of usage.

## ~ hint
 
**Bluetooth disabled**: This package disables BLE as the real time requirements of the WS2812 conflict with the BLE stack.

## ~

## Simulator support

The ``sendBuffer`` function is supported by the micro:bit simulator!

## License

MIT

## Supported targets

* for PXT/microbit

(The metadata above is needed for package search.)

# Forked from 
https://github.com/microsoft/pxt-ws2812b

