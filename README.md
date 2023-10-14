# Arduino AVR Boards

This is a customized version of arduino catherina bootloader to prevent any attacker dumping the firmware via USB.
Side effect: after flashing, arduino IDE won't be able to verify the firmware and reset the board, one has to reset manually

PS: to prevent firware dump via an SPI programmer, one should also set the lock bit via avrdude.
