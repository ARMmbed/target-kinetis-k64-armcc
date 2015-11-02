## yotta Target Description Using armcc v5 to Compile for Freescale Kinetis K64 Chips

This is a [yotta](https://github.com/ARMmbed/yotta) target description for
compiling for Freescale's Kinetis K64 family of microcontrollers. Currently
only the Mk64Fn1M0Vll12 is supported. You should not normally use this target
description directly, but instead use a more specific description of a target
board.

This target description inherits from the generic
[mbed-armcc](https://github.com/ARMmbed/target-mbed-armcc) target description,
which provides most of the information about how to run the compiler.

**To build for the FRDM K64F development board with armcc 5, use the
[frdm-k64f-armcc](https://github.com/ARMmbed/target-frdm-k64f-armcc) target
description** (which inherits from this one). The frdm-k64f target description
also provides a good starting point to copy if you are creating a new target
description for your own board using a K64F microcontroller.


