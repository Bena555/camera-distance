# Camera Distance

- Unlocks the 3rd person camera's maximum viewing distance.
- If you want the camera to be like the "Harrowhold camera" all of the time, then set the variable OVERRIDE_DEFAULT_SETTINGS to true and DEFAULT_MAX_DISTANCE to 1200. 
- You can customize the camera's max distance in-game by using the "!camera [distance]" command. 


## Chat commands:
!camera [distance]
### Examples:
- "!camera 1000"	sets the camera's current and maximum viewing distance to 1000
- "!camera 0"		will revert camera to use regular settings on next respawn (only if OVERRIDE_DEFAULT_SETTINGS is false)

Command is not case-sensitive.


## Info
- Normal camera's maximum distance is 500
- Harrohold camera's maximum distance is 1200
- By default, the current viewing distance (not max) when you login is 170


## Changelog 
### 1.1.0
* [+] Changed command to require exclamation prefix '!'
* [+] Added slash support

![Screenshot](http://i.imgur.com/LzxGSgm.jpg)