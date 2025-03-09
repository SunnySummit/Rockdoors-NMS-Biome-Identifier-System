# ROCKDOORS

[![License](https://img.shields.io/github/license/SunnySummit/Rockdoors-NMS-Biome-Identifier-System)](https://github.com/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/blob/main/LICENSE)
[![Downloads](https://img.shields.io/github/downloads/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/total.svg)](https://github.com/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/releases)
[![Stars](https://img.shields.io/github/stars/SunnySummit/Rockdoors-NMS-Biome-Identifier-System)](https://github.com/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/stargazers)
[![Issues](https://img.shields.io/github/issues/SunnySummit/Rockdoors-NMS-Biome-Identifier-System)](https://github.com/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/issues)
[![Version](https://img.shields.io/github/v/release/SunnySummit/Rockdoors-NMS-Biome-Identifier-System)](https://github.com/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/releases)

Tested/compatible with NMS version 5.58

### General

I used this to make Lasagna Etc - Highlights: https://www.nexusmods.com/nomanssky/mods/3386

+ This is a method for identifying planets in-game.
+ The folder contains 200 custom models, organized into 4 categories.
+ Each of these 4 categories is numbered from 1 to 50, each model has a unique texture ([comparison image](https://github.com/SunnySummit/Rockdoors-NMS-Biome-Identifier-System/blob/main/rockdoors%20compared.jpg)).
	+ 50 Reg - regular sized rockdoors
	+ 50 Small Float - floating small
	+ 50 Big - Largest
	+ 50 Tall - Just tall

### Instructions

1. Download Plumgen: https://github.com/SunnySummit/PLUMGEN/releases
2. Place '__NUMBERS_FOR_TESTING.csv' in '_Biome Templates' folder
3. Place '_____ROCKDOORS_TEST Worlds 22' folder in 'MODS'
4. Within Plumgen, right click 'New Biome' button -> generate 200 biomes (can be less, but NOT more)
5. Select '__NUMBERS_FOR_TESTING.csv' from the Biome Template dropdown menu
6. Select both checkboxes next to the dropdown menu
7. Select Tools > nums_for_testing. What this does:
+ A) adds unique rockdoors to all 200 biome objects
+ B) renames all biome object filenames
Now, in-game if you find e.g. a "tall" rockdoor with a number 12 on it, that means you're on "12_TALL" biome object.

Import back into Plumgen to further refine things.

### Credits:

+ Stone Arch by Daniyal Malik - https://sketchfab.com/3d-models/stone-arch-c444af1dc55d4ff3b9937bf1b20e65d6 License: CC Attribution
