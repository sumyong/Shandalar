# Game code

This repository contains the source code of the abandonware game Shandalar 1997 added with addtionnal cards up to 2015 cards from Magic The Gathering

## Contributing to the game

Your can fork the repository and send me pull request if you want to add some new features or cards in the game.

### Downloading code snapshots

You can download all the content of a branch via the "Code" button here on Github. You can then either clone the repository or simply download the selected branch content as a ZIP file.

**Important:** You always download the **entire branch content!**

You can then use the files locally on your hard drive.

### Running the game

To run the game, navigate into the folder and run Shandalar.exe (Windows only)

### Windows 11 dark screen after launch than exit

I was running Windows 7 64-bit home and had this same problem. Everything works fine except the launcher and shandalar. And luckily I found the fix just yesterday.

The trick is, to include MTGlauncher.exe and Shandalar.exe as exceptions to Window 7's Data Execution Prevention(DEP).

Note: You must have administrator access to do this

Go to My computer > Right click it and click Properties
At the left part of your window click > remote setttings
Click the Advanced Tab
Under Performance > Click Settings (the uppermost most button)
Now Click the Data Execution Prevention (DEP) tab
Select
o Turn on DEP for all programs and services except those I select

click add, and browse your MagicTG Folder(Game installation folder) and select MTGlauncher.exe

click add again then select Shandalar.exe

I tested this myself and shandalar should now work fine on your Windows 7 system
