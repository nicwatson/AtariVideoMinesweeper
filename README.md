# Atari Video Minesweeper
"Minesweeper" demake written in 6502 Assembly, for Atari 2600 systems (and emulators)

![watson_avmines](https://github.com/nicwatson/AtariVideoMinesweeper/assets/587252/31b7df6f-c12d-4206-9430-1c47b78be1f3)

## Compiling

The .dasm file contains the pre-assembly source code, written for the Atari 2600's MOS 6507 processor, suitable for assembly using the [_dasm macro assembler_](https://dasm-assembler.github.io/).
For best results, use DASM v2.20.10. Newer versions may produce a non-functioning binary.

## Pre-compiled binaries
If you just want to play the game, you need the .bin file with the assembled machine code (see Releases).
In order to execute it, you will need to install the free [Atari 2600 Stella emulator](https://stella-emu.github.io/).
Alternatively, if you have a physical Atari 2600 and a programmable multi-cartridge, you can use the .bin in combination with a [Harmony cartridge](https://harmony.atariage.com/Site/Harmony.html) to play on authentic hardware that pre-dates Minesweeper itself by over a decade!

## Gameplay Instructions

Use joystick to move cursor around on grid.
Reveal tiles selected by cursor by pressing fire button.
Note: When using an emulator, you may need to hold keys for a moment to get the game to respond.
 
Tiles are either empty, contain a number, or contain a landmine.
If you reveal a mine tile, you asplode!
A number indicates the number of mines somewhere adjacent to that tile.
Use deductive reasoning to determine the location of all the mines.
Flag known mine tiles with the Select switch on the console.  You have ten flags to place.
(You can remove a misplaced flag by pressing the select switch while the cursor is on the flag.)
There are ten mines in each grid.  Try to find and flag them all without accidentally blowing up!
Be careful: the clock is ticking!  At time 000 all the mines will go off.
After you win or lose, press Reset to play again.

## Screenshots

![Screenshot start](https://github.com/nicwatson/AtariVideoMinesweeper/assets/587252/75307259-26b4-4e26-829e-fd52ab5ad027)
![Screenshot play](https://github.com/nicwatson/AtariVideoMinesweeper/assets/587252/57bfc894-1bd3-4e27-98e9-29026942408c)
![Screenshot kaboom](https://github.com/nicwatson/AtariVideoMinesweeper/assets/587252/9c8e4f5c-d7b0-469d-95d4-bf896a6ee875)
