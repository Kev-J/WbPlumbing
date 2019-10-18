# WbPlumbing
Wishbone plumbing written in Chisel3. The aim of this project is mainly to
generate Wishbone intercon as described in [specification](https://github.com/fossi-foundation/wishbone).

# Modules description

## WbInterconPT

This is just a "passthrought" module, give one WbMaster bundle and one WbSlave
bundle in parameters and get the intercon module for your plumbing.

## WbInterconOneMaster

Make the address decoding for several slaves with the same data size. And with
only one master.

# Projects using WbPlumbing

* [MDIO](https://github.com/Martoni/MDIO): Generate ethernet phy MDIO protocol frame
* [Spi2Wb](https://github.com/Martoni/spi2wb): Drive a Wishbone master bus with SPI protocol.
