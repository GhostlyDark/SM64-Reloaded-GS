# SM64 Reloaded (GS)
SM64 Reloaded is an Ultra HD texture pack for [GLideN64](https://github.com/GhostlyDark/SM64-Reloaded), [Dolphin](https://github.com/GhostlyDark/SM64-Reloaded-Dolphin), [sm64pc](https://github.com/GhostlyDark/SM64-Reloaded-PC) and Ghostship.

![](/sm64-reloaded-gs.jpg)


## How to use OTR/O2R files
O2R files go into the `mods` directory. The order in which mods are loaded can be modified by changing file names. Release files have the `alt/` path prepended, which requires unhiding the menu pressing `Escape` and enabling `Use Alternate Assets` while in-game. Alternatively, press `Tab` to toggle the textures.


## Generate from PNG source
1. Install Ghostship by generating as many `.o2r` files as possible using supported ROMs. Check the Ghostship readme for supported versions.
2. Download [retro](https://github.com/HarbourMasters/retro/releases/latest).
3. Click `Create OTR / O2R -> Replace Textures -> No`, then select all available `.o2r` files at the same time. This will extract the textures from all archives and generates a `manifest.json`.
4. The compiled `manifest.json` needs to be copied into the directory that contains HD textures, mirroring the file structure of the extracted files. Overwrite any `.json` files included with this repository.
5. Choose `Create OTR / O2R -> Replace Textures -> Yes` and select the folder containing HD textures.
6. Keep files uncompressed to reduce stuttering. It is recommended to prepend `alt/` before staging textures, which allows assets to be toggled on-the-fly. Click `Stage Textures` to continue.
7. Click `Finalize OTR / O2R` and `Generate OTR / O2R` as the final step.
