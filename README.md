I didn't quite like the first version that I made as much as I was hoping I would. Enter, PRIDE-6 v2. An updated design with some extra overlays for Gameboy Color. I'll include the original PRIDE-6 overlays, just in case you'd like to have that option, but if you like v1 more than v2, feel free to head on over to the [v1 repository](https://github.com/otterbot/muOS-Overlays-PRIDE-6/tree/main).

Included are Gameboy Advance SP and Gameboy Color overlays with normal and holo-style bezels, with and without grids, with the necessary configuration files. Credit to AntiKK for allowing me to edit his overlays and use his config files because I can't code to save my life.

![alt_text](https://github.com/otterbot/muOS-Overlays-PRIDE-6-v2/blob/main/GBA%20Pride-6%20v2.png?raw=true)
![alt_text](https://github.com/otterbot/muOS-Overlays-PRIDE-6-v2/blob/main/GBC%20Pride-6%20v2.png?raw=true)

# File Placement
Move the **OtterBot** folder to `mmc > MUOS > retroarch > overlays`

# GBA Configuration

Open a GBA game, then the Quick Menu, and go back to the main menu. Then go to `Settings > Video > Scaling`.

Integer Scale: **Off**

Aspect Ratio: **Custom**

Custom Aspect Ratio (X Position): **0**

Custom Aspect Ratio (Y Position): **0**

Custom Aspect Ratio (Width): **640**

Custom Aspect Ratio (Height): **426**

Bilinear Filtering: **OFF**

Crop Overscan: **ON**

# GBC Configuration

Open a GBC game, then the Quick Menu, and go back to the main menu. Then go to `Settings > Video > Scaling`.

Interger Scale: **Off**

Aspect Ratio: **Custom**

Custom Aspect Ratio (X Position): **80**

Custom Aspect Ratio (Y Position): **24**

Custom Aspect Ratio (Width): **480 (3x)**

Custom Aspect Ratio (Height): **432 (3x)**

Bilinear Filtering: **OFF**

Crop Overscan: **ON**

# Usage
While playing a game, open the quick menu and go to `On-Screen Overlay > Overlay Preset`.

Select **Parent Directory** until you get to the directory that contains the folder named **OtterBot**. Then go to `OtterBot > gba` and pick which overlay you prefer.

Go back to the quick menu and then go to **Overrides**.

If you want the selected bezel for all GBA/GBC games, select **Save Content Directory Overrides**.

If you want the selected bezel for just the current GBA/GBC game, select **Save Game Overrides**.
