# Atari-2600
Exploratory projects for the Atari written in Assembly for the 6502 processor.

## Requirements:

You will need to need an emulator to run any of the ROMs:

- Stella installation

  Linux: </br>
  `sudo apt-get install stella`
  
  MacOS: </br>
  `brew install stella && brew link stella`
  
- Javatari (https://javatari.org) is a browser-based alternative with no downloads required. Might be more preferable on Windows machines.

- 8bitworkshop (https://8bitworkshop.com) is another great website for writing & debugging Assembly source code.
  
You will also need to download the DASM assembler over at https://dasm-assembler.github.io/ to translate the asm files to machine code.
  
To run any of the programs, navigate to the program's directory and run `make`. This will generate the cartridge binary file (`cart.bin`) for you to run in the emulator.

## Images:

Full display of the NTSC 128-color palette
<div align="center">
  <img src="https://raw.githubusercontent.com/Chrysippean/atari-2600/master/screenshots/rainbow.png" width="500" />
</div>

</br>

Bomber game inspired by the 1982 classic "River Raid"
<div align="center">
  <img src="https://raw.githubusercontent.com/Chrysippean/atari-2600/master/screenshots/bomber.png" width="500" />
</div>
