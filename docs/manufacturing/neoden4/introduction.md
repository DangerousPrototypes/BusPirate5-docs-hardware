---
sidebar_label: 'Introduction'
sidebar_position: 1
---

# Introduction
Bus Pirate v5 has over 200 component placements on one side, as well as a difficult to solder QFN Chip (the Raspberry Pi RP2040). To turn out prototypes without hours of backbreaking soldering we used a Neoden 4 Pick and Place gifted to us by the manufacturer in 2016/2017. 

The performance is far from optimal. Many parts are placed fine, while others are thrown across the room. It is totally inconsistent and a huge pain to work with, but it does still save a lot of time and effort.

## Toolchain
- [KiCad](https://kicad.org) Version 6 appears here, version 7+ is now available
- [KiCad-to-Neoden](https://github.com/szczys/kicad_to_neoden) Python script that converts KiCad .pos files to the Neoden format
