# first_antminer_s9_program_test

This repos contain the bitstream for the Antminer S9 board for demo testing.

## Usage
Since I only has a USB Blaster clone as the JTAG programmer, I used openFPGALoader:
```bash
openFPGALoader -c usb-blaster design_1_wrapper.bit
```
After the flashing is completed, LED D1 should be on and LED D7, D8, D5, D6 will be on with pattern 1010.
