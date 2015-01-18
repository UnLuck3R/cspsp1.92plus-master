----------------------------------------------------------------
Original website : http://cspsp.appspot.com/
Original forums  : http://s4.zetaboards.com/CSPSP/index/
Original guide   : http://s4.zetaboards.com/CSPSP/topic/9771063/1/
Original source  : https://github.com/kevinbchen/cspsp
Fixed source     : https://github.com/Leajian/cspsp
Kevin's blog     : http://kevinbchen.blogspot.com/
----------------------------------------------------------------
=================================================================
HOW TO COMPILE (on Windows) :
1) Download PSPSDK (FROM HERE ONLY) : http://sourceforge.net/projects/minpspw/files/SDK%20%2B%20devpak/pspsdk%200.10.0/pspsdk-setup-0.10.0.exe/download
2) Go to \cspsp\jge\Projects\cspsp and run clean.bat
3) Commit your changes to the code.
4) Compile (for 3xx kernel of course) by running mk3xx.bat
5) Just wait till it finishes, PATIENTLY. If you encounter problems, read the log and fix them.
	--------
	If you want to sign the EBOOT.PBP, so that it'll run without the need of CFW (Custom Firmware) :

	1) Go to \cspsp\sign_binaries and run once install.bat after the PSPSDK installation
	2) Now you can run sign.bat from \cspsp\jge\Projects\cspsp to sign the EBOOT.PBP
	--------
6) Copy the created EBOOT.PBP to \cspsp\jge\Projects\cspsp\bin folder
7) Copy and paste bin folder to Desktop and rename it to CSPSP
8) Copy CSPSP to your Memory Stick on ms0:/PSP/GAME folder
9) Run it on PSP.
(To recompile, repeat steps 2-5)

=================================================================
Fixes to original source by kamil09875 : http://s4.zetaboards.com/CSPSP/profile/3738995/
Uploaded on GitHub by Leajian
Small fixes and tweaks by Leajian
For full credits list, head to Original guide...
+++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++

CSPSP is a homebrew game for the Sony PSP, originally based heavily on Valve's popular Counter-Strike game. It's a two-dimensional overhead (top-down) shooter that features simple team gameplay and a variety of weapons.
CSPSP focuses heavily on multiplayer gameplay and is one of the most popular networked PSP homebrew games.
Some major features include: 
Completely free of charge
A total of 28 different weapons to take down enemies with, including knives, pistols, submachine guns, rifles, machine guns, and grenades
A quickly growing multiplayer community (there's almost always someone to play online)
A user account system with simple stats and friend lists
Hundreds of different maps
Fully-featured map editor (by coolguy5678) for the PC
Readily moddable (graphics, sound effects, gun configurations)

CSPSP is had been developed individually by Kevin Chen, though I've gotten help from a huge number of places. Some credit shoutouts:
ps2dev.org for information about anything related to programming on the PSP
James Hui for his JGE++ engine
Google for its awesome App Engine (which powers the entire online system)
Mark James for his beautiful Silk icon set
coolguy5678 for his map editor
The many mappers for maps that are actually fun to play on
His friends for (reluctantly :|) helping him test new versions and the fun
And of course, the players, for actually playing the game
Sorry if I've missed anyone important (I probably have). If you think someone should be credited, just drop me a message.