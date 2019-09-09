Script Title: 
DuckyScript-Windows-ChangeWallpaper

Author: 
dennis.n3dry

Duckencoder: 
2.6.3

Target: 
Windows 10

Description: 
If the User forgets to lock their computer,this script will utilize Microsoft Edge to download a wallpaper of Dennis Nedry from Jurrasic Park. It then sets the image as the curent wallpaper.

Customize the wallpaper by changing:
1. URL in string on line 15
2. The filename (make sure you leave the 'USERPROFILE/' portion)
3. The filename again on line 47. 

DEFAULTDELAY 250
DELAY 3000
GUI r
STRING microsoft-edge:https://i.ytimg.com/vi/K3PrSj9XEu4/maxresdefault.jpg
ENTER
DELAY 3000
GUI F11
DELAY 1500
PRINTSCREEN
ALT F4
GUI r
STRING mspaint
ENTER
DELAY 2000
CTRL v
ALT H
STRING RE
TAB
STRING 188
TAB
TAB
TAB
TAB
TAB
ENTER
CTRL s
STRING USERPROFILE\maxresdefault.jpg
ENTER
ALT F
STRING B
ENTER
ALT F4
GUI r
STRING cmd
ENTER
STRING Del maxresdefault.jpg
ENTER
ALT F4
GUI d
MENU
STRING r
TAB
TAB
TAB
TAB
TAB
STRING t
ENTER
ALT F4
END