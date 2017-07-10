
# casio-dungeons
Small dungeon game developed for CASIO fx-9x50 calculators.

# How to install (CASIO fx-9x50)
To install the game in an original CASIO fx-9x50, you'll need a cable to connect the computer to the calculator.
Once you have one, download CASIO FA-124 from https://edu.casio.com/education/support_software/dl/PC_links/fa124_inst_204_2.zip.
This program will allow you to upload files to the calculator.
Install it, and when it's done, open the program and connect your calculator to the computer. If it's via USB, a window will pop up on the calculator. Press [F1] to select recieve and transmit memory.
After that, go to FA-124 and click on the "Connect" icon from the Calculator window. This will connect the computer to the calculator.
Now, depending on what you want, you may grab these files to the "Default" folder of the FA-124 window:
[Not Required] LVLEDIT.G1M -> Allows the user to edit their own levels.
Uses (writes on) variables:
Mat A [Temporal]
List 26 (Items 1 and 2) [Temporal]
G, H, A, B, C, D, K [Temporal]

[Required] MODREND.G1M -> Used by the game for rendering levels. Used by both the level editor and the main game.
Doesn't write on any variable.

[Required] CASDUNG.G1M -> The main game.
Uses (Writes on) variables:
Mat A [Temporal]
List 26 (Items 1 and 2) [Temporal]
N, M, V, W, G, H, R, Q, C, D [Temporal]

Once it is on the "Default" folder, expand it, expand the "Program" folder, and move the already imported files you grabbed in to the "Program" folder from the calculator. Then, disconnect the cable.
Now you can play on your calculator! Just press MENU > 9, select RPG V2.0 (main game) or LVLEDIT (level editor) and press EXE to start.
Have fun!
