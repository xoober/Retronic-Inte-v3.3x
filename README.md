### Retronic USB Intellivision Firmware Modification

This firmware for the Retronic USB adapter for Intellivision controllers is a modification of [USBJoystickAdapter_v3.3](https://github.com/retronicdesign/USBJoystickAdapter_v3.3). It addresses a few issues with the official firmware. The eight buttons specific to Jzintv raw data bits can interfere with controller setup in some emulators and have been removed. The 16th button activated by keypad 1 & 9 combo can interfere with the internal Intellivision pause feature and has been removed. The following keypad combinations are now supported for external emulator functions, e.g. reset, exit, swap controller.

- keypad 5 and keypad Clear
- keypad 5 and keypad Enter
- keypad 4 and keypad Enter
- keypad 1 and keypad 8
- keypad 2 and keypad 9

Compatible with Retronic Design USB v3.x adapters. The programs to install Retronic USB firmware can be found at www.retronicdesign.com or at their Github linked above. To manually invoke the RetronicUSB update mode, hold and keep holding the upper side button on an Intellivision controller while connecting to the computer USB. With an Intellivision Flashback controller, hold keypad '6'.

Compiled with Microchip Studio v7.0. Only modified source code files are provided here. The rest of the source code can be found at [Intellivision_Controller_v3.3](https://github.com/retronicdesign/USBJoystickAdapter_v3.3/tree/main/Intellivision_Controller_v3.3) and at [Intellivision_Flashback_Controller_ATGames_v3.3](https://github.com/retronicdesign/USBJoystickAdapter_v3.3/tree/main/Intellivision_Flashback_Controller_ATGames_v3.3) for Intellivision Flashback controllers. This code is provided under a GPLv3 licence and does not offer any warranty whatsoever.

https://github.com/xoober/Retronic-Inte-v3.3x


