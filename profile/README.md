## Introduction
VLCB (Versatile Local Control Bus) is an initiative
by MERG members to improve CBUS<sup>TM</sup> by
clarifying issues and adding features for diagnostics
and troubleshooting.

Note: CBUS is a registered trademark owned by Dr M. Bolton.

A full description of why VLCB was created and how
it will achieve its goals are outlined in the document
[Executive Summary of VLCB](VLCB-Documents/Executive%20summary%20of%20VLCB.pdf)

## Specifications
Published versions of the VLCB specifications are located
in the [VLCB-Documents](https://github.com/Versatile-LCB/VLCB-documents) repository.

## Implementations

### VLCB Defs
The constants of various VLCB entities are kept in the
[VLCB-defs](https://github.com/Versatile-LCB/VLCB-defs)
repository. 
It contains generated files for many programming
languages to aid developing VLCB modules and tools
in any of these languages.

### PIC
Ian Hogg has developed a [library](https://github.com/spikyian/VLCBlib_PIC)
for implementing VLCB modules with PIC microprocessors.

Ian Hogg has also developed a VLCB version of the 
[Universal firmware](https://github.com/spikyian/Universal-VLCB)
using the PIC library above.

### Arduino
Sven Rosvall and Martin Da Costa has converted the CBUS
library created by Duncan Greenwood into a
[VLCB implementation](https://github.com/SvenRosvall/VLCB-Arduino).
This provides communication with the CAN bus using
the MCP2515 CAN transceiver. 
More implementations of other transceivers are being developed
but not yet publicly available.

### Conformance Test Suite
David Ellis has created a 
[test suite](https://github.com/david284/NPM-VLCB-CT)
to validate VLCB module implementations.
This is a crucial tool for ensuring that VLCB modules
follow the VLCB specifications.

## Contact Us

The VLCB Team consists of:
* Ian Hogg
* Martin Da Costa
* David Harris
* Duncan Greenwood
* Nigel Phillips
* David Ellis
* Sven Rosvall