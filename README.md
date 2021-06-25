# RDR Script Decompiler
A program that will decompile the script resources (XSC, CSC) files from both X360 and PS3 versions of Red Dead Redemption to High-Level.
SCOs are not supported mainly because they're not used by the game even if they are in the RPF container.

You must unpack the scripts with AreDeAre xPlorer to be able to use the decompiler properly (go to Tools/Unpack Resource). I may update the tool in the future to automatically decompress scripts in memory or even release the source if I ever feel the need to. Main reason I'm not releasing the source at the moment is to make sure people don't try to open and copy/paste functions or crack mod menus, yes this won't let you decompile most of the menus released for RDR (JediJosh Menu, Demonic Menus).
A lot of the code is still broken. It's either OpCodes are messed up or Rockstar was smoking something.
Some scripts contains branches that always ends up at the same place and doesn't do anything and fakes the reading.

Note that the .dll have to be in the same folder as the .exe
Decompiler is based on Zorg93 (NayJames93)'s decompiler made for Grand Theft Auto V.

Credits to Im Foxxyyy (me) and Zorg93 (NayJames93)

![Screenshot](screenshot.png)
