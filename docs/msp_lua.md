# msp_lua

*Author: Christof, Ruthgul*<br />
*Adapted from Christof's MSP plugin for Materia Magica*

### MSP (MUD Sound Protocol) emulation for Material Magica
---
#### Features:
* Provides support for triggered sound events from the game

#### Dependencies:
* MUSHclient world must be configured with MXP enabled
* Set SOUND must be set to ON in the game (enabled by default)

#### Aliases:
* **msp display**
  > Display a list showing the configured sound files path and file extension.

* **msp path** \<path>
  > Set the sound files path used to search for files matching the configured extension.

* **msp reset path**
  > Reset the configured sound files path.

* **msp type** \<extension>
  > Set the file extension to be used when searching for sound files.
