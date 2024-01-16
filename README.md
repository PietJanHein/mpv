This repository contains a basic mpv-setup with some changed hotkeys, added settings and added scripts. Tip, if your distro uses pipewire and you have problems with your soundcard then use "mpv --ao=pulse" to start mpv, it was required for my Soundblaster USB-soundcard.
Simply download the tar-archive and extract it in ~/.config/mpv. On Windows it works similarly but considering that I don't use Windows I would have to look up the directory where to extract it myself, it is somewhere in your users/<username>-directory. 

Added scripts: 
- go to the next or previous video in a directory, now with < and > 
- go to another chapter in a video (YouTube)
- go to another video in a playslit (by opening a playlist-link from YouTube) in mpv

Read the scriptfiles to understand how it works and in some cases what the hotkeys are. Usually functionally can be added to mpv by simply adding a file to the scripts-directory in ~/.config/mpv/
Pause with RMB because the LMB was required for the 2nd and 3rd script. 


All the hotkeys are in the input file. The defaults are hashtagged by the developer, you can change it by simply removing the # and changing the button. Scripts can interfere with the hotkeys which you set. 

Basic hotkeys: 
- pause: space/RMB/k
- skip time to a few seconds further: right arrow and l, alternatively shift+left/right for larger time-jumps (30 seconds give and take, it has to do with how videos are encoded)
- skip time to a few seconds earlier: left arrow and h
- volume: up and down arrow
- quit and remember time and values of volume and subtitles and all that for later: q
- quit and don't remember all that: shift+Q
- change fontsize of subtitles: shift+f/g
- cycle through audio tracks or subtitles, there are hotkeys for it (you can cycle in both directions) but you can also just click on the bar in the bottom 
- change speed: [ and ]

All the settings for mpv are in the config-file. 
