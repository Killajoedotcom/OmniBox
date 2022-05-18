---
title: Bill of Materials
summary: Guide to selecting and printing files for the OmniBox.
authors: Jon Harper
date: 2022-05-15
---

The design allows for screws of multiple lengths, i.e. to let you use what's on hand. The assembly process notes where substitutions can be made. This is a generic or "ideal" list.

## General Components

| Item                              | Qty | UOM | Note                                                     |
|-----------------------------------|-----|-----|----------------------------------------------------------|
| PLA or PLA+ filament              | 2   | kg  | May be printable in 1kg if using a single color          |
| M3 x 6mm machine screws           | 12  | ea  |                                                          |
| M3 x 8mm machine screws           | 12  | ea  | 4-8 more for the lid                                     |
| M3 x 12mm machine screws          | 8   | ea	|                                                          |
| M3 x 16mm machine screws          | 2   | ea  |                                                          |
| [#6 x 3/4" sharp point wood screws](https://www.amazon.com/gp/product/B08LV4D8SB) | 8   | ea  | Or M3 x 20mm; may also use machine screws |
| M4 x 8mm machine screws           | 14  | ea  |                                                          |
| M4 x 16mm machine screws          | 4   | ea  |                                                          |
| [SPST toggle switch](https://www.amazon.com/gp/product/B07QQ22DTB) | 1   | ea  | Identical profile to Creality Ender power switch |
| [Meanwell-type PSU](https://www.amazon.com/MEAN-WELL-LRS-350-24-350-4W-Switchable/dp/B013ETVO12) | 1   | ea  | Meanwell-type refers to mounting pattern (M4, 150mm x 50mm); compatible with most Ender-series PSUs |
| MCU (3D printer control board)    | 1   | ea  | Currently only the [BTT Octopus](https://www.amazon.com/BIGTREETECH-Motherboard-Compatible-Firmware-Raspberry/dp/B094NPRYDP) is supported, though a template is available  |
| SoC CPU (e.g., Raspberry Pi)      | 1   | ea  | (Optional) For OctoPrint/Klipper users; currently only Raspberry Pi 3B+ or 4B  are supported |
| [IEC C14 socket with fuse](https://www.amazon.com/gp/product/B081ZFHRGW) | 1   | ea  | Identical profile to Creality Ender series power socket  |
| [40x40x10mm fans](https://www.amazon.com/dp/B08R9L9YR2) | 2 | ea  | 5V, 12V, or 24V |
| A 12864-style display or emulator | 1   | ea  | Includes: Stock Creality 12864, Mini 12864 displays, and [BTT 3.5](https://www.amazon.com/BIGTREETECH-Upgrade-Touch-Controller-Display-Motherboard/dp/B07VWGFKLZ) displays |

## Optional Components

| Item                              | Qty | UOM |Note |
|-----------------------------------|-----|-----|-----|
| [USB C panel mount extension cable](https://www.amazon.com/gp/product/B086W7C58P/) | 1 | ea | Not needed if using UART with Klipper; any brand should work. |
| [MicroSD to MicroSD extension cable](https://www.amazon.com/gp/product/B09CKRDFTH) | 1 | ea | This is not the same profile as the more popular LANMU connector. |
| [LM2596 buck converters](https://www.amazon.com/Regulator-Adjustable-Converter-Electronic-Stabilizer/dp/B07PDGG84B/) | (varies) | ea | |
| [LM2596 buck converters with digital display](https://www.amazon.com/gp/product/B07N3QT628) | (varies) | ea | |

Other common components are solid state relays for controlling AC heated beds or external MOSFETs.
 
## Connectors

Only the IEC power connector is included in the Bill of Materials. The rear panel is meant to be customized by the end user, although you can still use a stock panel.

The two stock rear panel `.STL`s use JST SM connectors for everything but the hotend, which uses a 2-pin, 2-row [Molex Micro Fit 3.0](https://www.digikey.com/en/product-highlight/m/molex-connector/micro-fit-3-interconnect-system) panel mount connector.

### Hotend Connectors

These 2-pin, 2-row connectors can be found at Digikey:

- [Connector](https://www.digikey.com/en/products/detail/molex/0430200200/252490)
- [Pins](https://www.digikey.com/en/products/detail/molex/0430310009/252485)

!!! note
    These connectors have flaps on the side for panel mounting. The more commonly available part on Amazon is not compatible.

### JST SM Connector Kits

JST SM connectors kits are on [Amazon for about $15](https://www.amazon.com/gp/product/B07D9HRDT6).