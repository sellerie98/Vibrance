# Vibrance
My vibrance bash script to toggle colour vibrance on all active displays between default (0) and maximum (1023). Very useful for playing e.g. Counter-Strike on Linux with increased color vibrance when using proprietary nvidia graphics driver using nvidia-settings commands.

Depends on:
- nvidia
- nvidia-settings


If you want Steam to increase color vibrance for you with this script when starting csgo via Steam and disable it when you leave csgo again:
- Move the script into the folder where your csgo files are installed
- Enter `./vibrance; %command% <launch options, such as "-novid" etc.> && ./vibrance` as launch options on csgo in Steam
- profit
