# Super Mega Runners Vita

Port of Super Mega Runners to the PS Vita.

## Warning

Because this is the product of a decompilation, the source code will not be public; this repository is only for only for releases and bug reports.

## Controls

- Cross: Jump.
- Circle: Dash (only for Captain Kidd).
- Square: Use boost.
- D-pad: move left and right (only for Napoleon).
- All other controls are touch-based.

## Known Issues

- Some shaders look bad (but they are minor details).
- Buying coins doesn't work (and probably never will).
- Lag when there are too many objects on screen.
- There's a "view ad" button but it doesn't work (and probably never will).
- There's a share button but it doesn't work (and probably never will).
- Initial loading takes a bit.

## Requirements for installation

- Install Python.
- Run "pip install cryptography".

## Installation

- download SuperMegaRunVita.vpk and install it on your PS Vita.
- Download SuperMegaRunData.zip and extract the files to a folder.
- Now find and download the APK file for version 10.0 of the game, rename the file to "game.apk" and move it to the same folder as SuperMegaRunData.
- Run decrypt.py and if it asks for a password, just press enter.
- If everything went well, you should have a file called data.zip.
- Unzip the data.zip file.
- Move the extracted content from data.zip to "ux0:app/SMRV00000/".


