# MD_Mini_2_Exclusive_Games_Patch_Files
This repository contains bspatches for some of the Mega Drive Mini 2 (Genesis Mini 2) exclusive games so they can be run in third party emulators 
I can't add files for Space Harrier 1 & 2 because they run on imaginary hardware and currently cannot be emulated.
The patches for Vs. Puyo Puyo Sun do not make the game fully functional. The games with the applied patches are still playable, however.
Do not expect VS. Puyo Puyo Sun to be fully functional in the future.


# Instructions
1. In order to patch the games with these files, bsdiff needs to be installed: https://github.com/mendsley/bsdiff/tags
2. In order to get the games that need to be patched, you need to extract them from the MD Mini 2. Here is a link to get started: https://github.com/farmerbb/RED-Project/discussions/56
3. Download and extract this repository. (Hit the green code button on the main page and then download zip or use git commands).
4. Copy the games extracted from the system over to the newly downloaded folder with the bsdiff files. The games that need to be copied over are:
     - jp_jp_3rin_3chan.smd
     - jp_jp_devil_and_pii.smd
     - jp_jp_Fantasy_Zone.smd
     - jp_jp_puyopuyosun.smd
     - jp_jp_s_locomotive.smd
     - jp_jp_star_mobile.smd
     - us_us_puyopuyosun.smd
     - us_us_star_mobile.smd
5. Run the following commands in Linux:
     - ```bspatch jp_jp_3rin_3chan.smd Spatter.md jp_jp_3rin_3chan.bsdiff```
     - ```bspatch jp_jp_devil_and_pii.smd "Devil and Pii.md" jp_jp_devil_and_pii.bsdiff```
     - ```bspatch jp_jp_Fantasy_Zone.smd "Fantasy Zone.md" jp_jp_Fantasy_Zone.bsdiff```
     - ```bspatch jp_jp_puyopuyosun.smd "VS Puyo Puyo Sun (Japan).md" jp_jp_puyopuyosun.bsdiff```
     - ```bspatch jp_jp_s_locomotive.smd "Super Locomotive.md" jp_jp_s_locomotive.bsdiff```
     - ```bspatch jp_jp_star_mobile.smd "Star Mobile (Japan).md" jp_jp_star_mobile.bsdiff```
     - ```bspatch us_us_puyopuyosun.smd "VS Puyo Puyo Sun (USA).md" us_us_puyopuyosun.bsdiff```
     - ```bspatch us_us_star_mobile.smd "Star Mobile (USA).md" us_us_star_mobile.bspatch```
6. Load the new files in a Mega Drive/Genesis Emulator and hope that this works.

# Licensing
There is no licensing because I was not the person who originally patched the ROMs to work in third party emulators. If you are the person who created the original patched ROMs and want this repository taken down, please feel free to tell me in an issue.
