# DuckyScript-Windows-ChangeWallpaper

REM DuckyScript-Windows-ChangeWallpaper
REM
REM Author: dennis.n3dry
REM Duckencoder: 2.6.3
REM Target: Windows 10
REM Description: If the User forgets to lock their computer, this script will utilize Microsoft Edge to go and grab a picture
REM from Jurrasic Park showing Dennis Nedry and the famous line 'You didn't say the magic word'. Feel free to update the strings on 
REM line 14 and line 37 if you want to use your own image.
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
