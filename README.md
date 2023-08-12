# The World Ends With You: Solo Remix for the PS Vita
This repo contains patches that you can use in order to get fully working files for my port on TWEWY: Solo Remix, made for fuHEN.

Just a bit of warning; the complete file size of the game is around ``1.15 GB``. The patch files are around ``700 MB``. Make sure to save up space.

# Instructions
First, you might want to install the .VPK using VitaShell. Don't try to launch the game, because it will crash without the neccesary files.
Don't also forget to make a folder called ``TWEWY`` in ``ux0:data/``. It is neccesary in order to have your save data saved.

## Nintendo DS
- Go to the Release page and download ``patch_nds.zip``.
- Extract it somewhere and place your ROM of the game (make sure it's SHA1 hash is ``23e87b1e72aab7f9b718f83e92fd1c3039f23675``).
- Launch ``patch_game_ds.bat`` and type in the path to your ROM file.
- Let it finish and there should be a .ZIP file called ``data (drop contents at game dir).zip``.
- Open up VitaShell, connect your Vita to your PC and copy over the contents of the .ZIP file over to ``ux0:app/NEKU23850/Media``.
- Launch the game and have fun!

## Android
Note: The android version of the game is delisted. I used version 1.04 to create the patch files.

- Go to the Release page and download ``patch_mobile.zip``.
- Extract it somewhere.
- Get the contents of your .OBB file (you can generally find that in ``Android/obb/com.square_enix.android_googleplay.subarashikikonosekai_solo``) and put them in the root of the directory you crated for the patch files.
- Launch ``patch_game_mobile.bat`` and type in the path to a file called ``sharedassets1.assets`` (you can find that in ``OBB File -> ... -> sharedassets1.assets``).
- Let it finish and there should be a .ZIP file called ``data (drop contents at game dir).zip``.
- Open up VitaShell, connect your Vita to your PC and copy over the contents of the .ZIP file over to ``ux0:app/NEKU23850/Media``.
- Launch the game and have fun!
