TwoToneDetectDisplay
====================

Description
-----------
Displays call date and times that have been recorded by TwoToneDetect

HowTo
-----
Install the program by running ./install-ttdd as root
	this will configure the Raspberry Pi to auto-login, increase the display size, and run the program at boot.
	it will also copy the bash script into the /usr/local/bin directory named ttdd

Uninstall the program by running ./uninstall-ttdd as root

Change the Colors by changing the C1 and C2 numbers at the top of /usr/local/bin/ttdd
	available colors are numbered 0 through 7
	0 – Black
	1 – Red
	2 – Green
	3 – Yellow
	4 – Blue
	5 – Magenta
	6 – Cyan
	7 – White
 
More
-------
Created by: Kevin Ashcraft (http://kevashcraft.com) 
Created on: 2014-09-17
TwoToneDetect: https://sites.google.com/site/radioetcetera/twotoneprogram/ttd-on-a-pi
Source: https://github.com/kevashcraft/TwoToneDetectDisplay
