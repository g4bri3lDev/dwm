# DWM
DWM is a very simplistic tiling window manager which is all you need for a linux desktop.

## Keybindings
### open + close
   - <kbd>meta</kbd> + <kbd>enter</kbd>: open terminal
   - <kbd>meta</kbd> + <kbd>d</kbd>: open dmenu
   - <kbd>meta</kbd> + <kbd>e</kbd>: open emacs
   - <kbd>meta</kbd> + <kbd>r</kbd>: open vifm
   - <kbd>meta</kbd> + <kbd>w</kbd>: open browser
   - <kbd>meta</kbd> + <kbd>q</kbd>: close window
   
### navigation
   - <kbd>meta</kbd> + <kbd>[0-9]</kbd>: switch to tag
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>[0-9]</kbd>: move window to tag
   
   - <kbd>meta</kbd> + <kbd>j</kbd>: focus lower window in stack
   - <kbd>meta</kbd> + <kbd>k</kbd>: focus higher window in stack
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>j</kbd>: move window down in stack
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>k</kbd>: move window up in stack
   
   - <kbd>meta</kbd> + <kbd>space</kbd>: swap window with master
   - <kbd>meta</kbd> + <kbd>o</kbd>: move window to master stack
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>o</kbd>: move window from master stack
   
   - <kbd>meta</kbd> + <kbd>,</kbd>: focus monitor - 1
   - <kbd>meta</kbd> + <kbd>.</kbd>: focus monitor + 1
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>,</kbd>: tag monitor - 1
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>.</kbd>: tag monitor + 1
   
### layouts
   - <kbd>meta</kbd> + <kbd>b</kbd>: toggle bar
   
   - <kbd>meta</kbd> + <kbd>t</kbd>: tiling layout
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>t</kbd>: bstack horizontal layout
   
   - <kbd>meta</kbd> + <kbd>y</kbd>: spiral layout
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>y</kbd>: dwindle layout
   
   - <kbd>meta</kbd> + <kbd>u</kbd>: monocle layout
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>u</kbd>: bstack layout
   
   - <kbd>meta</kbd> + <kbd>i</kbd>: centeredmaster layout
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>i</kbd>: centeredfloatingmaster layout
   
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>p</kbd>: gaplessgrid layout
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>f</kbd>: null layout
   
### gap manipulation
   - <kbd>meta</kbd> + <kbd>z</kbd>: increase gaps
   - <kbd>meta</kbd> + <kbd>x</kbd>: decrease gaps
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>d</kbd>: toggle gaps
   
### other functions
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>q</kbd>: quit dwm
   - <kbd>meta</kbd> + <kbd>shift</kbd> + <kbd>x</kbd>: lock screen with slock
   
   - <kbd>meta</kbd> + <kbd>F3</kbd>: select display
   - <kbd>meta</kbd> + <kbd>F4</kbd>: open pulsemixer
   - <kbd>meta</kbd> + <kbd>F5</kbd>: select wallpaper
   - <kbd>meta</kbd> + <kbd>F9</kbd>: mount drive
   - <kbd>meta</kbd> + <kbd>F10</kbd>: unmount drive
   - <kbd>meta</kbd> + <kbd>F11</kbd>: open nmtui
   - <kbd>meta</kbd> + <kbd>F12</kbd>: open youtubedl dialog

## Patches

   - activetagindicator
   - bottomstack
   - centeredmaster
   - centered
   - fibonacci
   - gaplessgrid
   - hide_vacant_tags
   - noboarderfloatingfix
   - pertag
   - smartborders
   - statuscmd-signal
   - vanitygaps
   - warp
   - xrdb

## Additional requirements 

   > libxft-bgra
