#Arduino EEPROM read write API Example


The microcontroller on the Arduino and Genuino AVR based board has EEPROM: memory whose values are kept when the board is turned off (like a tiny hard drive). EEPROM library enables you to read and write those bytes. This repository provides an example of using the EEPROM to store and retrieve information.

Available memory to use on ATmega2560: 4096 bytes

Functions:
1. eeprom_clear(): clear eeprom memory
2. eeprom_crc(): check if eeprom memory contents changed or currupted
3. write_EEPROM(): write on eeprom memory
4. Read_EEPROM(): read from eeprom memory


