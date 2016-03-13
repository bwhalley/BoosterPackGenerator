# BoosterPackGenerator
A lightweight app that takes card images from folders and spits out print &amp; play booster pack sheets.

Made by Andy Wallace. AndyMakes.com
@andy_makes
andy@andymakes.com

Created using openFrameworks 0.8.4


------------------
Instructions
------------------

This app will create ready to print booster packs by drawing images from three folders (common, uncommon, rare) and randomly putting them into sets.

The card images can be of any size but they must all be the same size.
Any standard image format should work.

There is a settings.xml file that the app will look for that describes where the card images are and with what frequecy they should appear (among other things).
This file must be on the same level as the app.


------------------
Settings XML
------------------

Here is what each field does:

NUM_PACKS : How many packs to print

NUM_COMMON : How many common cards per pack
NUM_UNCOMMON : How many uncommon cards per pack
NUM_RARE : How many rare cards per pack

COMMON_SOURCE_FOLDER : path to the folder on your computer that contains the common card images
UNCOMMON_SOURCE_FOLDER : path to the folder on your computer that contains the uncommon card images
RARE_SOURCE_FOLDER : path to the folder on your computer that contains the rarcard images

OUTPUT_FOLDER : The path to the folder on your computer that the resulting printouts should go to. If the folder does not exist, the app will create it.

SHOW_PACK_NUMBERS : If set to "TRUE" a small box will appear at the bottom left corner showing the number of this pack. Useful because packs may be spread across several sheets.

CLOSE_WHEN_FINISHED : If set to "TRUE" the app will exit automaticly once it is done creating the sheets

EDGE_PADDING : The amount of white space (in pixels) around the edge of each sheet
CARD_PADDING : The amount of white space (in pixels) between each card