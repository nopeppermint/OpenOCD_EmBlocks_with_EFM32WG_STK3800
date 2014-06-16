OpenOCD_EmBlocks_with_EFM32WG_STK3800
=====================================

OpenOCD example with ST-Link/V2, EmBlocks and EFM32WG_STK3800
_____________________________________________________
Copy all the emblocks folders into the corresponding examples in

$(APPDATA)\Roaming\energymicro\kits\EFM32WG_STK3800
_____________________________________________________
You have to connect an St-Link/V2 to the 20pin debug header on the EFM32WG_STK3800 board.

Don't forget to change in the energyAwareCommander under Kit/DebugMode to "In".

The EFM32WG_STK3800 board must be connected via usb to the computer, otherwise you won't be
abel to use the debug in port!
_____________________________________________________
For more information look also here:
https://github.com/nopeppermint/openocd_efm32