# kicad-keyboard-parts.pretty

## This repository is deprecated and will not be updated. It has been replaced by [marbastlib](https://github.com/ebastler/marbastlib).
Marbastlib features more components, uses the KiCAD 6.0 library formats, and is frequently updated in collaboration with 
[MarvFPV](https://github.com/marvfpv). Some of the new footprints: A full library of Cherry MX and Kailh Choc footprints (hotswap and regular, incl. stabilizers), revmount common anode RGB LEDs, WS2812B_2020, HRO Type-C M14 mid-mount-USB connectors and more.

This library will remain untouched in order not to break projects that depend on it, but I would recommend switching to our new library for upcoming designs. If you find any errors, please report them to me - I will still fix errors in this library.

### Symbols:
 * TP4056 - 1S LiIon linear battery charge/protection IC
 * DW01A - 1S LiIon protection IC
 * FS8205 - Dual MOSFET to be used with the DW01A
 * XC6206PxxxMR - LDO
 * nRF52840_holyiot_18010 - nRF52840 module from holyiot
 * TXB0101 - 1-Bit bidirectional levelshifter
 * WS2812B-MINI (to be used with KiCAD base SK6812MINI footprint)
 * MX_LED - a symbol to be used with ai03s MX keyswitch lib, offering split symbols for LED and switch for cleaner matrix drawing
 * BAV70_Small - smaller symbol to the BAV70 common cathode diode for better use in a switch matrix
 * SK6812MINI-E - symbol for SK6812MINI-E (different pin order than regular MINI)

### Footprints
 * ECE ESP3020 - Vertical SMD slide-switch, 20V 0.5A
 * nRF52840_holyiot_18010 - nRF52840 module from holyiot. Bottom IO only solderable with reflow.
 * nRF52840_holyiot_18010_HS_simple - nRF52840 module from holyiot. Bottom pads removed.
 * nRF52840_holyiot_18010_HS_all - nRF52840 module from holyiot. Hole in PCB + pads up to the PCB edge to solder bottom pads from the other side. Currently untested - use at you own risk (and please report back to me if you do)
 * MX_SK6812MINI-E - SK6812 MINI-E (reverse mount) RGB LED add-on intended to be used with any regular MX switch footprint like ai03's lib
 * MX_SK6812MINI-E_REV - Same as above, but with 180° rotated LED

 ### 3D Models
 Note: If you put the submodule directly into your kicad project folder, all custom footprints have working 3D model file paths.
 * JST SH (2, 4, 5, 6, 8 pins) ([source](https://grabcad.com/library/jst-sh-smd-connectors-1/details?folder_id=3903823))
 * WS2812B-MINI / SK6812MINI ([source](https://grabcad.com/library/smd-ws2812b-led-1))
 * SK6812MINI-E
 * Alps SKQG style SMD switch ([source](https://grabcad.com/library/5mm-button-switch-1))
 * 1206 SMD polyfuse ([source](https://grabcad.com/library/0zcj0075af2e-1))
 * HRO TYPE-C-31-M-12 ([source](https://grabcad.com/library/type-c-31-m-12-1))
 * ECE ESP3020
 * holyiot 18010 nRF52840 (thanks darryldh)
 * Alps EC11E and EC11N series 3D models ([source](https://tech.alpsalpine.com/e/products/cad.html))
 * Kailh hotswap socket 3D model ([source](https://grabcad.com/library/kailh-hotswap-mx-1))