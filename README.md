
# QoL: Unknown
### Quality of Life & Discord Rich Presence Mod for Casualties: Unknown
<div align="center">
<img width="458" height="auto" alt="Mod Icon" src="https://github.com/user-attachments/assets/96fe38ed-0df2-4a25-95f6-498e4627938f">
</div>


<div align="center">
  
[![Latest Release](https://img.shields.io/github/v/release/jimmyking9999999/QoL-Unknown?include_prereleases&color=orange&logo=github)](https://github.com/jimmyking9999999/QoL-Unknown/releases/latest)
[![Total Downloads](https://img.shields.io/github/downloads/jimmyking9999999/QoL-Unknown/total?color=blue&logo=github)](https://github.com/jimmyking9999999/QoL-Unknown/releases)
![Game Version](https://img.shields.io/badge/Game_version-v5.0.3-green)

</div>

## Overview

This mod is a general quality of life mod for [Casualties: Unknown](https://orsonik.itch.io/scav-prototype), meant to introduce accessibility and QoL features without changing the core mechanics of the game. 

This mod works alongside all other public mods!

## Features
<details>
<summary><strong>UI, UX, Visuals</strong></summary>
<br>

*   Automatic integrated Discord Rich Presence game support
*   Line of sight is enhanced
*   Adjustable luminosity and bloom settings
*   Brain Damage text scrambling is slightly less intrusive
*   Added up/down arrow navigation to select different choices for autofill in the console
*   Console `spawn` command now autofills and has a visual guide
*   Added Unicode font support for ZH and other languages
*   Enhanced the crafting menu item preview
<kbd>
<img width="448" height="184" alt="image" src="https://github.com/user-attachments/assets/21be03c0-8182-4666-a6ba-eb4b0c6f29b9" />
</kbd>

</details>

<details>
<summary><strong>Inventory</strong></summary>
<br>

*  Quick-transfer for liquids and items via `Shift + Drag`
*  Inventory auto-sort, prioritizing saved slots at low total weight, and lowest weight otherwise
*  Scroll bars for containers that go offscreen
*  Quick item pickup using middle-mouse button
<kbd>
  <img src="https://github.com/user-attachments/assets/3898e7f5-5c83-4aae-80cd-b4eab6437833" width="957">
</kbd>

</details>

<details>
<summary><strong>Gameplay</strong></summary>
<br>

*   Mid-layer saves that retain world generation, traps, enemies, etc...
*   1-tile water no longer pushes the player, and water physics is more lenient
*   Seeded runs for consistent worlds. (This syncs worlds down to the same keycode and items from drop pods!)
*   Layer modifiers are able to be adjusted individually (e.g., enabling only dried layers)
*   Difficulty sliders are no longer restricted
<kbd>
<img width="1263" height="426" alt="image" src="https://github.com/user-attachments/assets/77c1b3b8-9edf-4496-80b6-30b3c9902a4c" />
</kbd>

</details>

<details>
<summary><strong>System, Customization</strong></summary>
<br>
  
*   In-game options menu
*   In-game custom keybind page
*   Master volume & sound slider
*   Controller support for Xbox/XInput-based controllers
*   Individual entity density options. This can increase geysers amounts if you really like them, or remove spiders fully if you have arachnophobia
*   Individual structure density options (if you really (don't) want lifepods or other structures)
*   One-click locale download button
*   Pre-run skill point allocation
*   Framerate, resolution, window settings
*   Individual sound overrides, audio safety toggles
*   Instant radline toggle
<kbd>
<img width="1364" height="805" alt="image" src="https://github.com/user-attachments/assets/7294c336-d216-4c1e-88ef-689341ba41fc" />
</kbd>
  
</details>
<br>

**Note:** Almost all features listed above include toggles for customization.


## Installation

Please follow these steps exactly to ensure your mod loads correctly!
<details> 
<summary><strong>Windows</strong></summary>
  
### A: Installing the Mod Loader (BepInEx)

1.  Download **BepInEx v5.4.23.4** (x64) from the official repository:
    *   [Download BepInEx_win_x64_5.4.23.4.zip](https://github.com/BepInEx/BepInEx/releases/download/v5.4.23.4/BepInEx_win_x64_5.4.23.4.zip)
2.  Navigate to your *Casualties: Unknown* game folder (the folder containing `CasualtiesUnknown.exe`).
3.  Extract the contents of the downloaded zip file directly into this folder.
4.  If prompted, choose to "Replace all files."
5.  Run the game once to generate the necessary configuration folders, then close the game.
6.  If you have a `BepInEx/Plugins` folder, you have done this correctly!

### B: Installing QoL: Unknown

1.  Navigate to your game folder and open the newly created path: `BepInEx/Plugins`.
2.  Download the mod DLL file:
    *   [Download QoL Unknown.dll](https://github.com/jimmyking9999999/QoL-Unknown/raw/refs/heads/main/QoL%20Unknown.dll)
3.  Place the `QoL Unknown.dll` file inside the `BepInEx/Plugins` folder.
4.  Launch the game.

Your filesystem should look as follows: 
```
CasualtiesUnknownDemo/
└── BepInEx/
    └── plugins/
        ├── QoL Unknown.dll
        └── (as well as any additional mods!)
```

https://github.com/user-attachments/assets/601b786c-ff3f-444a-b3ad-11cf8e08b927

</details>

<details> 
<summary><strong>Linux</strong></summary>
  
### A: Installing the Mod Loader (BepInEx)

1. Install wine & winetricks: `pacman -Sy wine winetricks`
2. Install dependencies for Unity: `winetricks dotnet40 dotnet48 dotnet8 dotnet9 dotnetcore3 dotnetcoredesktop3 dotnetdesktop8 dotnetdesktop9 arial corefonts`
3.  Download **BepInEx v5.4.23.4** (x64) from the official repository:
    *   [Download BepInEx_win_x64_5.4.23.4.zip](https://github.com/BepInEx/BepInEx/releases/download/v5.4.23.4/BepInEx_win_x64_5.4.23.4.zip)
    *   Note that you **must** download the win_x64 version
4.  Extract the contents of the downloaded zip file directly into the C:U game folder.
5.  Open up winecfg `winecfg`, and add `winhttp.dll` as a dll override (`Libraries⁩⁩⁩⁩⁩⁩⁩⁩`)
6.  Launch the game and close it. If you have a `BepInEx/Plugins` folder, you have done this correctly!

### B: Installing QoL: Unknown

1.  Navigate to your game folder and open the newly created path: `BepInEx/Plugins`.
2.  Download the mod DLL file:
    *   [Download QoL Unknown.dll](https://github.com/jimmyking9999999/QoL-Unknown/raw/refs/heads/main/QoL%20Unknown.dll)
3.  Place the `QoL Unknown.dll` file inside the `BepInEx/Plugins` folder.
4.  Launch the game.
5.  To enable Discord RPC, read [here](https://github.com/ValveSoftware/Proton/wiki/Enabling-Discord-Rich-Presence)
  
</details>

## Additional Information

Source code is not provided, due to the developer's stance on non-approved modding. However, this will change on the game's steam release :)

As such, pull requests and code contributions cannot be accepted. However, suggestions, issue reports regarding bugs, or installation difficulties are welcome in the Issues tab or in the [Discord](https://discord.gg/VeCSKv7AKa) [thread](https://ptb.discord.com/channels/955738554129063947/1453362863417720832)!
