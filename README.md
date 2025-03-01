![ToggleSlot Footprint](image.png)
# toggleSlot
A PCB footprint which adds power switching ability to a coin cell holder.

UPDATE:

Coin cell batteries can kill a child if swallowed. It is now mandatory that coin cell batteries be secured behind a secondary layer of protection. This design lacks that protection and it therefore should not be used. See [Reese's Law](https://www.reesespurpose.org/reeseslaw)

The Consumer Product Safety Commission regulation on this topic can be read [here](https://www.cpsc.gov/Business--Manufacturing/Business-Education/Business-Guidance/Button-Cell-and-Coin-Battery)

More broadly, almost all simple coin cell holders lack a secondary locking mechanism, so many other products which employ them, even in a standard configuration, are in violation of [16 CFR Part 1263](https://www.federalregister.gov/documents/2023/09/21/2023-20333/safety-standard-for-button-cell-or-coin-batteries-and-consumer-products-containing-such-batteries)

I've taken down the footprint files. The rest of this repo is up as a notice to anyone who might be searching for similar ideas in the future. 

## Description

This repository contains the KiCad symbol and footprint libraries for toggleSlot:

Symbol library: toggleSlot.kicad_sym

Footprint library: toggleSlot.pretty

## Installation

To use these libraries in KiCad, follow these steps:

Download the repository.

Add the symbol library (toggleSlot.kicad_sym) in KiCad's Symbol Libraries manager.

Add the footprint library (toggleSlot.pretty) in KiCad's Footprint Libraries manager.

While any appropriate symbol can be used with this footprint, the suppplied symbol is pre-linked to the right footprint for convenience. 

## Usage

The negative or "on" pad (labeled N1 in the image above) must have a small amount of solder applied to it for the purpose of raising the surface of the pad high enough to make contact with the underside of the battery. 

![gif](usage.gif)

## License

[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)
