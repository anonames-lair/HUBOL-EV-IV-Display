# HUBOL-EV-IV-Display
Original: https://github.com/Acimut/Custom-EV-IV-Display-Screen

Specially configured for HUBOL DPE/CFRU. With the same build requirments as the original. `config.mk` configured to inject at `0x800000`.

## Screenshot
![screenshot](https://i.imgur.com/a23noiy.png)

## Instruction
1. Obtain the original program by Acimut
2. Take the files in this repository and replace the corresponding ones in the original program
3. Install required programs Acimut mentioned (also including `preproc.exe` and `gbagfx.exe` in your PATH environment variable)
4. Once you have everything set up, follow the instructions for setting the offset in `config.mk` and renaming the rom to `CFRU.gba`
5. Finally, you should be ready to compile by running `make` in the terminal, and a rom with the injection will appear in a folder called `build`
